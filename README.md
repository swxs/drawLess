# geometry.less author : swxs date : 2016/6/23

文件类型less

使用css完成几何图形的绘制，实现大小的简易自定义

//通用矩形绘制(IE6+)
.rect(@width:10px, @height:10px, @color:#000)

//通用正方形绘制(IE6+)
.square(@width:10px, @color:#000)

通用等腰三角绘制(IE6+)
.isoscelesTriangle(top, @Height:10px, @borderWidth:10px, @Color:#000)
.isoscelesTriangle(bottom, @Height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(left, @Height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(right, @Height:10px, @borderWidth:10px, @color:#000)
.isoscelesTriangle(top, @Height:10px, @topAngle:90deg, @Color:#000)
.isoscelesTriangle(bottom, @Height:10px, @topAngle:90deg, @Color:#000)
.isoscelesTriangle(left, @Height:10px, @topAngle:90deg, @Color:#000)
.isoscelesTriangle(right, @Height:10px, @topAngle:90deg, @Color:#000)


通用直角三角绘制(IE6+)
.rightTriangle(top-right, @Height:10px, @borderWidth:10px, @Color:#000)
.rightTriangle(top-left, @Height:10px, @borderWidth:10px, @Color:#000)
.rightTriangle(bottom-right, @Height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(bottom-left, @Height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(left-top, @Height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(left-bottom, @Height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(right-top, @Height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(right-bottom, @Height:10px, @borderWidth:10px, @color:#000)
.rightTriangle(top-right, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(top-left, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(bottom-right, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(bottom-left, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(left-top, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(left-bottom, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(right-top, @Height:10px, @topAngle:90deg, @Color:#000)
.rightTriangle(right-bottom, @Height:10px, @topAngle:90deg, @Color:#000)








//  平行四边形
//  .parallelogram(@width:10px, @height:10px, @angleX:0, @angleY:0, @backgroundColor:#000)
//  
//  矩形
//  .rect(@width:10px, @height:10px, @backgroundColor:#000)
//  
//  正方形
//  .square(@width:10px, @backgroundColor:#000)
//  

//  
//  梯形
//  .trapezoid(top, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  .trapezoid(bottom, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  .trapezoid(left, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  .trapezoid(right, @topWidth:10px, @borderHeight:10px, @bottomWidth:10px, @borderColor:#000)
//  
// 	圆
//  .circle(@width:10px, @backgroundcolor:#000, @borderWidth: 10px, @borderColor: #000)
//
// 	椭圆
//  .ellipse(@width:10px, @height:20px, @angleX:0, @angleY:0, @backgroundColor:#000, @borderWidth: 10px, @borderColor: #000)
//  
//  扇形
//
//  五角星
//  .star-five(@borderHeight:10px, @borderColor:#000)
//  
//  六角星
//  .star-six(@borderHeight:10px, @borderColor:#000)
//   
//  八角星
//  .star-eight(@borderHeight:10px, @borderColor:#000)
//  
//  十二角星
//  .star-twelve(@borderHeight:10px, @borderColor:#000)
//  
//  五边形
//  .pentagon(@border:10px, @borderColor:#000) 
//  
//  六边形
//  .hexagon()(@border:10px, @borderColor:#000)
//  
//  八边形
//  .Octagon()
//  


