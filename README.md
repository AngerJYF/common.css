### css 初始化样式

``` css

html, body { height: 100%; }
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: "Arial", "Microsoft YaHei", "PingFangSC-Regular", "SimSun", "宋体"; }
h1, h2, h3, h4, h5, h6 { margin: 0; padding: 0; }
ul, li, ol, dl, dt, dd { list-style: none; }
a { text-decoration: none; }
a:hover, a:focus { text-decoration: none; outline-style: none; }
em { font-style: normal; }
.clearfix::after { content: ""; display: block; height: 0; line-height: 0; clear: both; visibility: hidden; }
.clearfix { *zoom: 1; }
input { outline: none; }


input:-webkit-autofill {
  -webkit-box-shadow: 0 0 0px 1000px white inset !important;
  border: 1px solid #979797 !important;
}
[v-cloak] {
  display: none;
}
/*滚动条样式*/
::-webkit-scrollbar {
  /*滚动条整体样式*/
  width: 8px; /*高宽分别对应横竖滚动条的尺寸*/
  height: 8px;
  border-radius: 5px;
}

::-webkit-scrollbar-thumb {
  /*滚动条里面小方块*/
  border-radius: 5px;
  /*-webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.2);*/
  /* background: rgba(243, 243, 243, 0.397); */
  background: rgba(112, 111, 111, 0);
}
:hover::-webkit-scrollbar-thumb{
  background: rgba(112, 111, 111, 0.3);
}
::-webkit-scrollbar-track {
  /*滚动条里面轨道*/
  /*-webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.2);*/
  border-radius: 5px;
  /* background: rgba(1, 56, 99, 0.719); */
  background: rgba(1, 56, 99, 0);
}


/*媒体查询*/
/* 超小屏幕（手机，小于 768px） */
@media screen and (max-width: 340px){
	
}
@media screen and (min-width: 340px) and (max-width: 768px){
	
}
/* 小屏幕（平板，大于等于 768px） */
@media screen and (min-width: 769px) and (max-width:992px){
	
}
/* 中等屏幕（桌面显示器，大于等于 992px） */
@media screen and (min-width: 993px) and (max-width:1200px){
	
}
/* 大屏幕（大桌面显示器，大于等于 1200px） */
@media screen and (min-width: 1201px) and (max-width:1366px){
	
}
@media screen and (min-width: 1367px) and (max-width:1550px){
	
}
@media screen and (min-width: 1551px) and (max-width:1920px){
	
}
@media screen and (min-width: 1921px){
	
}


```
