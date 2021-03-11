# 背景图片如何不重复居中呈现

## css代码
    .banner {
      background: url("img/banner.png");
      height: 600px;
      background-repeat: no-repeat;
      background-position: 50%;
    }  
 
 注意的点有，要记得写高度，不要使用 
 
    .banner{background-img:url{../..}}

背景图片居中显示使用
    
    .banner{background-position:50%}