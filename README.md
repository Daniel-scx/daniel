/*三行分别是字体粗细（整百数字），字体样式，字体阴影*/
*{font-weight:500!important;}
*{font-family: “Microsoft Yahei”, “Microsoft Yahei” !important; }
*{text-shadow:0.01em 0.01em 0.01em #999999 !important;}
/*滚动条*/
::-webkit-scrollbar{width: 6px;height: 6px;}
::-webkit-scrollbar-track-piece{background-color: #CCCCCC;-webkit-border-radius: 6px;}
::-webkit-scrollbar-thumb:vertical{height: 5px;background-color: #999999;-webkit-border-radius: 6px;}
::-webkit-scrollbar-thumb:horizontal{width: 5px;background-color: #CCCCCC;-webkit-border-radius: 6px;}
::-webkit-scrollbar {width: 9px;height: 9px;}
::-webkit-scrollbar-track-piece {background-color: transparent;}
::-webkit-scrollbar-thumb {background-color: #3994EF;border-radius: 3px;}
::-webkit-scrollbar-thumb:hover {background-color: #A4EEF0;}
::-webkit-scrollbar-thumb:active {background-color: #666;}
::-webkit-scrollbar-button:vertical { width: 9px; }
::-webkit-scrollbar-button:horizontal { width: 9px; }
::-webkit-scrollbar-button:vertical:start:decrement { background-color: white; }
::-webkit-scrollbar-button:vertical:end:increment { background-color: white; }
::-webkit-scrollbar-button:horizontal:start:decrement { background-color: white; }
::-webkit-scrollbar-button:horizontal:end:increment { background-color: white; }
body::-webkit-scrollbar-track-piece {background-color: white;}
/*指向图片蓝光*/
img:hover{box-shadow: 0px 0px 3px 3px rgba(0,191,255,0.3) !important;-webkit-transition-property: box-shadow;-webkit-transition-duration: .31s;}
img{-webkit-transition-property: box-shadow;-webkit-transition-duration: .31s;}
/*输入框美化*/
input { border:#ccc 1px solid; border-radius: 6px; -webkit-border-radius: 6px;}
input[type=”text”]:focus, input[type=”password”]:focus, textarea:focus {border: 2px solid #6FA1D9 !important;-webkit-box-shadow:0px 0px 5px #6FA1D9 !important;outline:none}
input[type=”checkbox”]:focus,input[type=”submit”]:focus,input[type=”reset”]:focus, input[type=”radio”]:focus {border: 1px solid #6FA1D9 !important; outline:none}
input:focus, select:focus, textarea:focus {outline: 1px solid #10bae0 ;-webkit-outline-radius: 3px ;}
body a:hover:active {color: #10bae0;}
/*body *:focus {outline: 2px solid rgba(16,186,224,0.5) ;outline-offset: 1px ; -moz-outline-radius: 2px ;-webkit-outline-radius: 2px ;}*/
body a:focus {outline-offset: 0px ;}
body button:focus,
body input[type=reset]:focus, body input[type=button]:focus, body input[type=submit]:focus {-moz-outline-radius: 2px !important;-webkit-outline-radius: 2px !important;}
body textarea:focus, body button:focus, body select:focus, body input:focus {outline-offset: -1px !important;}
/*淡蓝色样式*/
a{-webkit-transition: all 0.3s ease-out;}
a:hover{color: #39F !important;text-shadow:0.1px 0.1px 0.1px #39F !important;-webkit-transition: all 0.3s ease-out;}
*::-webkit-selection {background: #333333 !important; color: #00FF00 !important; }
/*去除下划线*/
*{text-decoration:none!important}
a:hover{text-decoration:none!important}
a{
/*color: #014A8F;*/
-webkit-transition-property:color;
-webkit-transition-duration: 0.0s;
}
/*不更改以下ICONFONT*/
/**:not([class*="icon"]):not(i){font-family: "Microsoft YaHei" !important;}*/
* {font-family: "Microsoft YaHei","iconfont","FontAwesome","octicons","Bootstrap","glyphicon" !important;}

