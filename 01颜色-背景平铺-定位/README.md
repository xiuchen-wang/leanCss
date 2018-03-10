1.单位  
px em 百分比 cm mm  
2.颜色  
  (1)单词 red blue (2)gab(204,0,255) (3)十六进制 #CC00FF  
3.背景  
    a.单一样式  
	  (1)背景颜色 background-color:  
	  (2)引入背景图片 background-image:url(); (默认状态下背景会平铺)    
	  (3)不平铺 backgound-repeat:no-repeat;  
	           backgound-repeat:repeat-x;(指定平铺方向)  
	           backgound-repeat:repeat-y;  
	  (4)背景图片级别高于背景颜色。  
	  (5)背景的定位： background-position：100px 300px;(x轴  Y轴)  
	                background-position：20% 10%；     
	                background-position：left|right|center  top|center|bottom  
	                background-position：left; (y轴默认center)  
	                background-position：bottom;(x轴默认center)  
	                background-position：center;  
	  (6) background-repeat:repeat-x;  
	      background-position:20px 0px; (左侧不会空白 会补图)   
	  (7) 改变背景图片大小 background-size:300px 200px         
	  (8)背景固定 background-attachment:fixed;(默认scroll可以滚动)                 
    b.复合样式(属性的位置可以改变)  
       background:#ccc url(../xx.jpg) no-repeat 100px 200px fixed;  
