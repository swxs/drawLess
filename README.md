# geometry.less 

### 该Less提供了几何图形绘制的一系列实现方法

### 矩形绘制{I}(IE6+)
- .rect(@width:10px, @height:10px, @color:#000)
- .rect(@width:10px, @heightScale:1, @color:#000)

### 正方形绘制{I}(IE6+)
- .square(@width:10px, @color:#000)

### 三角形绘制{I}(IE6+)
- .triangle(SAS, @leftBorder:10px, @topAngle:90deg, @rightBorder:10px,@color:#000)

### 等腰三角形绘制{I}(IE6+)
- .isoscelesTriangle(top/bottom/left/right, @height:10px, @borderWidth:10px, @color:#000)
- .isoscelesTriangle(top/bottom/left/right, @height:10px, @topAngle:90deg, @color:#000)

### 直角三角形绘制{I}(IE6+)
- .rightTriangle(top-right/top-left/bottom-right/bottom-left/left-top/left-bottom/right-top/right-bottom, @height:10px, @borderWidth:10px, @color:#000)
- .rightTriangle(top-right/top-left/bottom-right/bottom-left/left-top/left-bottom/right-top/right-bottom, @height:10px, @topAngle:90deg, @color:#000)

### 等腰梯形绘制{I}(IE6+)
- .isoscelesTrapezoid(top/bottom/left/right, @height:10px, @topWidth:10px, @bottomWidth:10px, @color:#000)
- .isoscelesTrapezoid(top/bottom/left/right, @height:10px, @topWidth:10px, @topAngle:90deg, @color:#000)

### 直角梯形绘制{I}(IE6+)
- .rightTrapezoidtop-right/top-left/bottom-right/bottom-left/left-top/left-bottom/right-top/right-bottom, @height:10px, @topWidth:10px, @bottomWidth:10px, @color:#000)
- .rightTrapezoid(top-right/top-left/bottom-right/bottom-left/left-top/left-bottom/right-top/right-bottom, @height:10px, @topWidth:10px, @topAngle:90deg, @color:#000)


### 圆形绘制{I}(IE9+)
- .circle(@radius:10px, @color:#000)

### 1/4圆形绘制{I}(IE9+)
- .quarterCircular(top/bottom/left/right,@radius:10px, @color:#000)

### 半圆形绘制{I}(IE9+)
- .halfCircular(top-right/top-left/bottom-right/bottom-left/left-top/left-bottom/right-top/right-bottom,@radius:10px, @color:#000)

### 3/4圆形绘制{I}(IE9+)
- .threeQuartersCircular(top/bottom/left/right,@radius:10px, @color:#000)


# iconico.less 

### 该Less提供了复合图形绘制的一系列实现方法

### 三角形绘制{II}(IE9+)
- .ico-triangle(ASA, @leftAngle, @bottomSide:10px, @rightAngle, @color:#000, @backgroundColor:#fff)

### 五角星绘制{III}(IE9+)
- .ico-star-five(@height:10px, @color:#000)

### 六角星绘制{II}(IE9+)
- .ico-star-six(@height:20px, @color:#000)

### 八角星绘制{II}(IE9+)
- .ico-star-eight(@height:20px, @color:#000)

### 十二角星绘制{III}(IE9+)
- .ico-star-twelve(@height:20px, @color:#000)

### 五边形绘制{II}(IE9+)
- .ico-border-five(@border:10px, @color:#000)

### 六边形绘制{II}(IE9+)
- .ico-border-six(@border:10px, @color:#000)

### 八边形绘制{III}(IE9+)
- .ico-border-eight(@border:10px, @color:#000)

### 心形绘制{III}(IE9+)
- .ico-heart(@border:10px, @color:#000)

### 阴阳图绘制{III}(IE9+)
- .ico-yin-yang(@radius:40px, @color:#000)

### author : swxs date : 2016/6/23




