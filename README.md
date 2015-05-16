### [Demo](http://polly343900.github.io/demo/zoom/index.html).

![演示](http://7sbqpj.com1.z0.glb.clouddn.com/record.gif)

这次算是一个完整的JS插件/模块了吧。不过看了很多插件在最后还得destroy变量和监听器，目前我只写了init。

对requireJS初步学习了下，这次是初次试用。^_^

前端真是路漫漫啊~

#####使用说明

```javascript
var z = document.getElementById('zoomer');
    zoom.init(z,{
        ratio: 2
    });
```