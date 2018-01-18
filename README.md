### videojs 一个兼容IE8的js视频播放框架

##### First one the videojs offical website click [videojs](http://www.videojs.com)

页面中引入的三个js一个不能少 顺序不要换 另外需要注意的是这行代码

```
videojs.options.flash.swf='/video-js.swf';
```

这行代码告诉videojs swf文件在什么位置 用于在videojs发现浏览器不支持HTML5播放器的时候自动唤起flash播放器 如果多次尝试在IE8下依然不行 请检查你的 video-js.swf文件路径是否正确