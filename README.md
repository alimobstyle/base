# base

---

重置样式/常用类

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/base.css">

### 常用类

````html
<style>
/*文字居中对齐*/
.center {
    text-align: center;
}
/*文字居右对齐*/
.text-right {
    text-align: right;
}
/*更大号字体*/
.larger {
    font-size: 1.125em;
}
/*更小号字体*/
.smaller {
    font-size: .875em;
}
/*黑色字体*/
.black {
    color: #333;
}
/*灰色字体*/
.gray {
    color: #808080;
}
/*橙色字体*/
.orange {
    color: #f60;
}
/*禁止中文输入*/
.ime-disabled {
    ime-mode: disabled;
}
/*清除浮动*/
.fn-clear:after {
    visibility: hidden;
    display: block;
    font-size: 0;
    content: " ";
    clear: both;
    height: 0;
}
body .fn-hide {
    display: none;
}
/*浮动*/
.fn-left, .fn-right {
    display: inline;
}
.fn-left {
    float: left;
}
.fn-right {
    float: right;
}
/*fix定位*/
.ali-fixed {
    position: fixed;
}
.ali-fixed-bottom {
    left: 5px;
    right: 5px;
    bottom: 0;
}
/*flexbox布局*/
.ali-flexbox {
    display: -webkit-box;
    display: -ms-flexbox;
    display: box;
}
.ali-flexbox .ali-flexbox-item {
    -webkit-box-flex: 1;
    -ms-flex: 1;
    box-flex: 1;
    margin: 4px 0 4px 8px;
}
.ali-flexbox-item:first-child {
    margin-left: 0;
}
</style>
````
