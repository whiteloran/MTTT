<head>
<meta name="viewport" content="width=device-width,initial-scale=1.0, minimum-scale=0.1, maximum-scale=1.0, user-scalable=no"/>
<style type="text/css">
	#important {margin:0 auto !important};
	#cross {margin:0 auto !important};
	#tipic {margin:0 auto !important};
	p {font-size:1.2em !important;font-family:Arial,Helvetica,sans-serif !important;line-height:8px};
	td {font-size:1em !important;font-family:Arial,Helvetica,sans-serif !important};
	li {font-size:1em !important;font-family:Arial,Helvetica,sans-serif !important};
	select {font-size:1em !important;font-family:Arial,Helvetica,sans-serif !important};
</style>
<audio controls="controls" hidden="hidden" autoplay="autoplay" loop="loop"><source src="./bgm.mp3" type="audio/mpeg"/></audio>
</head>
<body>

<img id="tipic" src="M.svg" style="zoom:50%" />
<p id="cross"></p>
<img id="tipic" src="Title.svg" style="zoom:200%"/>

<p><font size=1.1rem><i>“往往是那些善良的愿望，把人类带入了人间地狱。”——[德]荷尔德林</i></font></p>

- <font size=1rem>仅需购点方法完成角色建立</font>
- <font size=1rem>对抗骰法完成成功检定</font>
- <font size=1rem>轻量化、模板化、对象化的魔法少女TRPG规则</font>

<script type="text/javascript">
     //调整浏览器窗口大小事件 
    window.onresize = function(){
        _autoZoom();
    }
    _autoZoom();
    function _autoZoom(){
         var svg = document.getElementById("main");
        if (svg) {
            svg.setAttribute("preserveAspectRatio", "xMinYMin meet");
            svg.setAttribute("viewBox", "0 0 1452 860");
            svg.style.overflow = "hidden";
            var viewBoxVal = svg.getAttribute("viewBox");
            if (viewBoxVal) {
                var viewBoxWidth = viewBoxVal.split(" ")[2];
                var viewBoxHeight = viewBoxVal.split(" ")[3];
                svg.removeAttribute("width");
                svg.removeAttribute("height");

                var setWidth = document.body.clientWidth;
                var setHeight = setWidth * viewBoxHeight / viewBoxWidth;
                svg.setAttribute("width", setWidth);
                svg.setAttribute("height", setHeight);
            }
        }
    }
</script>

[Get Started](documents/home.md)

</body>

