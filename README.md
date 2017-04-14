# Ads
PC端JavaScript原生广告轮播插件

特点：`向下兼容至IE6`，`原生插件`，`体积小`

* `使用方法`：

```javascript
var ads=new Ads({
	"container":"slider",//广告轮播容器id
	"control":"slider_control",//广告轮播控制容器id 子元素必须为span元素
	"onClass":"on",//控制按钮高亮样式类名
	"useHover":true,//切换控制的方式 默认false 
	"stay"://3000广告停留时间 默认3e3
});
```
* `扩展函数`:

```javascript
ads.Next();//跳转下一帧
ads.Prev();//跳转上一帧
);
```

* [`关于作者`](http://www.douchaoyang.com)
