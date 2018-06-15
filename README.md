# ie-css3.htc
css3兼容ie6.7.8
使用方法：
        样式中增加  behavior: url(项目绝对路径ie-css3.htc); 
注意事项：
        当前元素一定要有定位属性，position:relative或position:absolute。
        z-index值一定要比周围元素的要高
        http协议访问
        原生IE浏览器访问，兼容模式显示可能没效果
支持样式：
        border-radius  只设置一个角落的圆角属性时无效
        box-shadow     只支持#(000）黑色阴影
        text-shadow    IE下样式表现与Firefox/Safari/Chrome存在差异，原因不详
