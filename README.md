# ezos-flexible

[Classic edition (1.0.1)](https://github.com/WuYunlong/ezos-flexible/tree/master)

> 由于`viewport`单位得到众多浏览器的兼容，`lib-flexible`这个过渡方案已经可以放弃使用，不管是现在的版本还是以前的版本，都存有一定的问题。建议大家开始使用`viewport`来替代此方。

> 本项目是 `amfe-flexible` 的替代产品, 相比 `amfe-flexible` 增加了灵活的配置，比如我们在在电脑上看到页面的时候可以设定最大宽度，方便用户在电脑端浏览我们的页面，使用 `window` 全局变量来进行更改

## Usage

#### Install

`npm i -S ezos-flexible`

#### Import

```html
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no">
<script >
	window.REM_MAX_NUMBER = 7.5
	window.BODY_MAX_WIDTH = 750
</script>
<script src="./node_modules/ezos-flexible/index.js"></script>
```
