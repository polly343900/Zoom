### [Demo1](http://polly343900.github.io/demo/zoom/index.html)

### [Demo2](http://polly343900.github.io/demo/zoom/demo2.html)

#### 演示1（演示gif有点大，加载要一定时间）

![演示](http://7sbqpj.com1.z0.glb.clouddn.com/record.gif)

####演示2

![演示2](http://7sbqpj.com1.z0.glb.clouddn.com/record2.gif)

这次算是一个完整的JS插件/模块了吧。不过看了很多插件在最后还得destroy变量和监听器，~~目前我只写了init。~~

#####使用说明

```javascript
var z = document.getElementById('zoomer');
    zoom.init(z,{
        ratio: 2
    });
```

可选参数示例如下：

```javascript
 var defaults = {
        url: '',  // 图片url
        ratio: 1,  // 初始图片比例
        pace: 0.5  // 点击加减按钮时图片缩放幅度
    }
```