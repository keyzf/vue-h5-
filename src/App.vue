<template>
    <div id="app">
        <router-view></router-view>
    </div>
</template>
<style>
/* CSS reset */
html{color:#000;background:#FFF;font-family:Arial,'Microsoft Yahei';}
body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,code,form,fieldset,legend,input,button,textarea,p,blockquote,th,td,strong{padding:0;margin:0;font-family:Arial,'Microsoft Yahei';}
body {font-size: 12px;}
table{border-collapse:collapse;border-spacing:0;}
fieldset,img{border:0;}
a{text-decoration:none; color:#000; outline:none;}/*此处待添加默认链接颜色*/
var,em,strong,b,i{font-style:normal;font-weight: normal;}
address,caption,cite,code,dfn,em,strong,th,var, optgroup{font-style:inherit;font-weight:inherit;}
del,ins{text-decoration:none;}
li{list-style:none;}
caption,th{text-align:left;}
h1,h2,h3,h4,h5,h6{font-size:100%;font-weight:normal;}
legend{color:#000;}
input,button,textarea,select,optgroup,option{font-family:inherit; font-size:inherit;font-style:inherit;font-weight:inherit;}
input,button,textarea,select{*font-size:100%;}
.clearfix:after {content:"\200B"; display:block; height:0; clear:both; }
.clearfix { *zoom:1; }
</style>