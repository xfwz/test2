<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="viewport" content="initial-scale=1.0, user-scalable=no" />
 	<script src="http://api.map.baidu.com/api?v=1.4"></script>
	<style>
		#allmap{width:100%;height:460px;overflow:hidden;border:1px solid black;}
		#allmap p{ padding:0px; margin:0px;}
		.aac{ font-size:14px; color:#c35c00; text-align:center; font-weight:bold;}
	</style>
</head>
<body>
	<div id="allmap"></div>
	<script type="text/javascript">
			var map = new BMap.Map("allmap");            // 创建Map实例
			var point = new BMap.Point(114.276964,30.600574); // 创建点坐标
			map.centerAndZoom(point,30);                 // 初始化地图,设置中心点坐标和地图级别。
			map.enableScrollWheelZoom();                 //启用滚轮放大缩小

			var marker = new BMap.Marker(point);  // 创建标注
			map.addOverlay(marker);               // 将标注添加到地图中
			marker.setAnimation(BMAP_ANIMATION_BOUNCE); //跳动的动画

			//    创建地图左边缩放滚轮
		    map.addControl(new BMap.NavigationControl());
		    map.addControl(new BMap.ScaleControl());
		    map.addControl(new BMap.OverviewMapControl());

		    var marker = new BMap.Marker(point);                        
		    map.addOverlay(marker);
		    var infoWinOpts = {}
		    var infoWin = new BMap.InfoWindow(
		    	"<div style='text-align:left;color:#1A6DAF;'><p class='aac'>焦作乐舞艺术培训中心</p><p>报名电话：张老师 15993779223</p><p>　　　　　张老师 13569102874</p><p>电　话：0391-8336394</p><p>邮　箱：53556122@qq.com</p><p>地　址：河南省·焦作市·华商大厦四楼（五楼）西区</p><p>网　址：www.lewuyishu.com</p></div>",infoWinOpts);
		    marker.openInfoWindow(infoWin);
		    marker.addEventListener("click", function(){this.openInfoWindow(infoWin);});
</script>
</body>
</html>

