# geometry.less author : swxs date : 2016/6/23

文件类型less

使用css完成几何图形的绘制，实现大小的简易自定义

矩形绘制[I](IE6+)
.rect(@width:10px, @height:10px, @color:#000)

正方形绘制[I](IE6+)
.square(@width:10px, @color:#000)

等腰三角形绘制[I](IE6+)
.isoscelesTriangle(top, @height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(bottom, @height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(left, @height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(right, @height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(top, @height:10px, @topAngle:90deg, @color:#000)
.isoscelesTriangle(bottom, @height:10px, @topAngle:90deg, @color:#000)
.isoscelesTriangle(left, @height:10px, @topAngle:90deg, @color:#000)
.isoscelesTriangle(right, @height:10px, @topAngle:90deg, @color:#000)

直角三角形绘制[I](IE6+)
.rightTriangle(top-right, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(top-left, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(bottom-right, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(bottom-left, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(left-top, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(left-bottom, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(right-top, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(right-bottom, @height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(top-right, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(top-left, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(bottom-right, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(bottom-left, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(left-top, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(left-bottom, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(right-top, @height:10px, @topAngle:90deg, @color:#000)
.rightTriangle(right-bottom, @height:10px, @topAngle:90deg, @color:#000)

//  梯形
//  .trapezoid(top, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  .trapezoid(bottom, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  .trapezoid(left, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  .trapezoid(right, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)

三角形绘制[II](IE6+)
.triangle(ASA, @leftAngle, @bottomSide:10px, @rightAngle, @color:#000, @backgroundColor:#fff)

五角星绘制[III](IE8+)
.star-five(@height:10px, @color:#000)
六角星绘制[II](IE6+)
.star-six(@height:20px, @color:#000)
八角星绘制[II](IE6+)
.star-eight(@width:20px, @color:#000)
十二角星绘制[III](IE6+)
.star-twelve(@width:20px, @color:#000)




//  平行四边形
//  .parallelogram(@width:10px, @height:10px, @angleX:0, @angleY:0, @backgroundColor:#000)
//
//  五边形
//  .pentagon(@border:10px, @borderColor:#000) 
//  
//  六边形
//  .hexagon()(@border:10px, @borderColor:#000)
//  
//  八边形
//  .Octagon()

// 	圆
//  .circle(@width:10px, @backgroundcolor:#000, @borderWidth: 10px, @borderColor: #000)
//
// 	椭圆
//  .ellipse(@width:10px, @height:20px, @angleX:0, @angleY:0, @backgroundColor:#000, @borderWidth: 10px, @borderColor: #000)
//  扇形
//  心形
//  新月
//  阴阳



