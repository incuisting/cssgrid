# cssgrid
****
####使用
引入文件（假设放在和html同级目录下）
```html
<link rel="stylesheet" type="text/css" href="grid.css">
```
栅格需要包裹在一`row`里，如下：
```html
<div class="row">
        <div class="col-md-4 col-sm-6">1-1</div>
        <div class="col-md-4 col-sm-6">1-2</div>
        <div class="col-md-4 col-sm-12">1-3</div>
</div>
```
####响应式
- 屏幕小于768px，`col-xs`生效   
- 屏幕在769px与991px之间，`col-sm`生效   
- 屏幕在992px与1199px之间，`col-md`生效   
- 屏幕大于1200px，`col-lg`生效