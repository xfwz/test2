# test2
这是一个测试项目
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>{$DT["sitename"]}</title>
    <meta name="keywords" content="{$keywords}" />
    <meta name="description" content="{$description}" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="format-detection" content="telephone=no">
    <meta name="renderer" content="webkit">
    <meta http-equiv="Cache-Control" content="no-siteapp"/>
    <!--网站样式-->
    <link rel="stylesheet" href="{DT_SKIN}css/amazeui.min.css"/>
    <link rel="stylesheet" href="{DT_SKIN}css/reset.css"/>
    <link rel="stylesheet" href="{DT_SKIN}css/font-awesome.css"/>
    <link rel="stylesheet" href="{DT_SKIN}css/common.css"/>
    <link rel="stylesheet" href="{DT_SKIN}css/style.css"/>
    <link rel="stylesheet" href="{DT_SKIN}css/media.css"/>
    <link rel="stylesheet" href="{DT_SKIN}css/animate.css"/>

    <!--ie 样式-->
    <!--[if lt IE 9]>
    <link rel="stylesheet" type="text/css" href="{DT_SKIN}css/browser.css"/>
    <![endif]-->

    <!--网站js-->
    <script type="text/javascript" src="{DT_SKIN}js/jquery-1.9.1.min.js" charset="utf-8"></script>
    <script type="text/javascript" src="{DT_SKIN}js/amazeui.min.js" charset="utf-8"></script>
    <script type="text/javascript" src="{DT_SKIN}js/common.js" charset="utf-8"></script>

    <!--ie6兼容-->
    <!--[if IE 6]>
    <script type="text/javascript" src="{DT_SKIN}js/DD_belatedPNG_0.0.8a-min.js"></script>
    <script type="text/javascript">
        DD_belatedPNG.fix('*');
    </script>
    <![endif]-->
    <!--[if IE]>
    <script src="{DT_SKIN}js/html5shiv.min.js"></script>
    <![endif]-->
    <!--[if lte IE 8]>
    <script src="{DT_SKIN}js/ie_browser.js"></script>
    <![endif]-->
</head>
<body style="background-color: #f7f7f7;">

{template "header"}

<div class="banner contact_banner wow fadeInDown animated" data-wow-delay="0.6s">
    <img src="{DT_SKIN}images/contact_banner.jpg" alt=""/>
</div>
<!--banner end-->

<!--百度地图-->
<div id="allmap"></div>


<!--鑫灵锐分公司地图 begin-->
<div class="map" id="map">
    <div class="hubei" id="hubei">
        <ul id="UL_demo">
            <li title="黄石" class="huangshi">黄石</li>
            <li title="宜昌" class="yichang">宜昌</li>
            <li title="潜江" class="qianjiang">潜江</li>
            <li title="仙桃" class="xiantao">仙桃</li>
            <li title="荆州" class="jinzhou">荆州</li>
            <li title="黄冈" class="huanggang">黄冈</li>
            <li title="孝感" class="xiaogan">孝感</li>
            <li title="天门" class="tianmen">天门</li>
            <li title="咸宁" class="xiannin">咸宁</li>
            <li></li>
            <span title="武汉" class="wuhan">武汉</span>
        </ul>
    </div>

    <div class="Popup Popup2">
        <img src="{DT_SKIN}images/map/hover/map_logo.png" alt="logo" class="map_logo"/>
        <h3>武汉鑫灵锐信息技术有限公司</h3>
        <p>湖北省统一业务咨询热线：<span>027-85842782</span></p>
        <p>湖北省统一客户服务热线：<span>400-027-2782</span></p>
        <p>手　　机：13667290585</span></p>
        <p class="location">地　　址：<span>湖北省汉口江汉区建设大道564号国贸新都Ｂ座27楼Ｅ－Ｆ室</span></p>
    </div>

    <div class="Popup Popup3">
        <img src="{DT_SKIN}images/map/hover/ck_logo.png" alt="logo" class="map_logo"/>
        <h3>武汉鑫灵锐信息技术有限公司</h3>
        <p>湖北省统一业务咨询热线：<span>027-85842782</span></p>
        <p>湖北省统一客户服务热线：<span>400-027-2782</span></p>
        <p>手　　机：13667290585</span></p>
        <p class="location">地　　址：<span>湖北省汉口江汉区建设大道564号国贸新都Ｂ座27楼Ｅ－Ｆ室</span></p>
    </div>
    <div class="Popup Popup4">
        <img src="{DT_SKIN}images/map/hover/map_logo.png" alt="logo" class="map_logo"/>
        <h3>武汉鑫灵锐信息技术有限公司</h3>
        <p>湖北省统一业务咨询热线：<span>027-85842782</span></p>
        <p>湖北省统一客户服务热线：<span>400-027-2782</span></p>
        <p>手　　机：13667290585</span></p>
        <p class="location">地　　址：<span>湖北省汉口江汉区建设大道564号国贸新都Ｂ座27楼Ｅ－Ｆ室</span></p>
    </div>
</div>
<!--鑫灵锐分公司地图 end-->

    <div class="Popup Popup1" id="Popup1">
        <img src="{DT_SKIN}images/map/hover/map_logo.png" alt="logo" class="map_logo"/>
        <h3>武汉鑫灵锐信息技术有限公司</h3>
        <p>湖北省统一业务咨询热线：<span>027-85842782</span></p>
        <p>湖北省统一客户服务热线：<span>400-027-2782</span></p>
        <p>手　　机：13667290585</span></p>
        <p class="location">地　　址：<span>武汉市光谷新世界新尚都B座28楼2801室</span></p>
    </div>
<!--弹出层-->


<!--项目内容 begin-->
<div class="project contact_project">
    <div class="am-container">
        <div class="fl">
            LINKS
        </div>
        <div class="fr">
            <ul>
                <li>
                    <a href="">牛商网</a>
                    <a href="">牛商网</a>
                    <a href="">牛商网</a>
                    <a href="">牛商网</a>
                </li>
                <li>
                    <a href="">全网营销培训</a>
                    <a href="">全网营销培训</a>
                    <a href="">全网营销培训</a>
                    <a href="">全网营销培训</a>
                </li>
                <li>
                    <a href="">营销型网站建设</a>
                    <a href="">营销型网站建设</a>
                    <a href="">营销型网站建设</a>
                    <a href="">营销型网站建设</a>
                </li>
                <li>
                    <a href="">网站建设</a>
                    <a href="">网站建设</a>
                    <a href="">网站建设</a>
                    <a href="">网站建设</a>
                </li>
                <li>
                    <a href="">网站托管</a>
                    <a href="">网站托管</a>
                    <a href="">网站托管</a>
                    <a href="">网站托管</a>
                </li>
                <li>
                    <a href="">手机网站建设</a>
                    <a href="">手机网站建设</a>
                    <a href="">手机网站建设</a>
                    <a href="">手机网站建设</a>
                </li>
            </ul>
        </div>
    </div>
</div>
<!--项目内容 end-->

<!--footer-->
<div class="footer">
    <div class="am-container">
        <div class="fl">
            <ul>
                <li>
                    <dl>
                        <dt>鑫灵锐产品<p>PRODUCT</p></dt>
                        <dd>
                            <a href="#">营销型网站</a>
                            <a href="#">手机网站</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">网站代运营</a>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt>鑫灵锐服务<p>SERCVICE</p></dt>
                        <dd>
                            <a href="#">营销型网站</a>
                            <a href="#">手机网站</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">网站代运营</a>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt>鑫灵锐案例<p>CASE</p></dt>
                        <dd>
                            <a href="#">营销型网站</a>
                            <a href="#">手机网站</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">网站代运营</a>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt>关于鑫灵锐<p>ABOUT US</p></dt>
                        <dd>
                            <a href="#">营销型网站</a>
                            <a href="#">手机网站</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">移动推广系统</a>
                            <a href="#">网站代运营</a>
                        </dd>
                    </dl>
                </li>
            </ul>
        </div>
        <div class="weixn fr">
            <dl>
                <dt><img src="{DT_SKIN}images/weixin.png" alt="weixin" /> </dt>
                <dd>微信扫一扫</dd>
            </dl>
        </div>
    </div>
</div>

<!--版权 begin-->
<div class="copyright">
    <div class="am-container">
        <p>© 2012-2015 武汉鑫灵锐信息技术有限公司 版权所有 鄂ICP备12004144号-1 </p>
        <p>地址：武汉市江汉区建设大道564号国贸新都B座27楼E-F室 电话：400-027-2782　027-85842782　手机：13667290585</p>
    </div>
</div>
<!--版权 end-->

<script type="text/javascript" src="{DT_SKIN}js/map.js" charset="utf-8"></script>
<script type="text/javascript" src="http://api.map.baidu.com/api?v=2.0&ak=9C53GZNHEF6mGB5WH5m1VybbvrYCPmkH"></script>
<script type="text/javascript">
    // 百度地图API功能
    var map = new BMap.Map("allmap");
    var point = new BMap.Point(114.276617,30.601039);  //坐标
    map.centerAndZoom(point, 15);
    var marker = new BMap.Marker(point);  // 创建标注
    map.addOverlay(marker);               // 将标注添加到地图中
    marker.setAnimation(BMAP_ANIMATION_BOUNCE); //跳动的动画

    var opts = {
        position : point,    // 指定文本标注所在的地理位置
        offset   : new BMap.Size(30, -30)    //设置文本偏移量
    }

    // 窗体信息
    var label = new BMap.Label("地址：湖北省武汉市江汉区建设大道564号国贸新都B座27楼G室", opts);  // 创建文本标注对象
    label.setStyle({
        color : "red",
        fontSize : "12px",
        height : "20px",
        lineHeight : "20px",
        fontFamily:"微软雅黑"
    });
    map.addOverlay(label);


    // 鼠标缩放地图
    // map.centerAndZoom("武汉",12);
    // map.enableScrollWheelZoom();   //启用滚轮放大缩小，默认禁用
    // map.enableContinuousZoom();    //启用地图惯性拖拽，默认禁用


    // 鼠标右键放大缩小
    var menu = new BMap.ContextMenu();
    var txtMenuItem = [
        {
            text:'放大',
            callback:function(){map.zoomIn()}
        },
        {
            text:'缩小',
            callback:function(){map.zoomOut()}
        }
    ];
    for(var i=0; i < txtMenuItem.length; i++){
        menu.addItem(new BMap.MenuItem(txtMenuItem[i].text,txtMenuItem[i].callback,100));
    }
    map.addContextMenu(menu);

</script>
</body>
</html>
