## 图片跟随鼠标

HTML:
```html
  <img src="image.jpg" id="targetImage">
```

CSS样式:
```css
#targetImage {
    position: absolute;
    display: inline-block;
    width: 100px;
    height: 100px;
}
```

js代码：
```javascript
let targetImage = document.getElementById('targetImage');
console.log(targetImage)
// 第一种写法
document.onmousemove = function(event) {
    var x = event.clientX;
    var y = event.clientY;
    targetImage.style.left = x + 'px';
    targetImage.style.top = y + 'px';
}

// 第二种写法
document.addEventListener('mousemove', function(event) {
    var x = event.clientX;
    var y = event.clientY;
    targetImage.style.left = x + 'px';
    targetImage.style.top = y + 'px';            
})

// offsetLeft, offsetTop 是相对于包含块（一般是父元素）的偏移量，而 clientX, clientY 是相对于视口（浏览器窗口）的坐标。
// scrollLeft, scrollTop 是元素滚动条的偏移量，而 pageX, pageY 是相对于整个文档的坐标。
// scorllWidth, scrollHeight 是元素内容的总宽度和高度，而 clientWidth, clientHeight 是元素可视区域的宽度和高度。
```
