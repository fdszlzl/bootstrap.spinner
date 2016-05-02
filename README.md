# bootstrap.spinner
基于bootstrap2的数字加减器

- HTML
```html
<input type="text" class="spinner">
```

- 调用
```javascript
$(".spinner").spinner([options])
```

- 选项
```javascript
{
  max: null, //加减器的最大值
  min: null, //加减器的最小值
  step: 1, //步长
  change: null, //加减器改变时的回调
  add: null, //加减器增加时的回调
  sub: null //加减器减少时的回调
}
```
