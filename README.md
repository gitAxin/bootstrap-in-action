# bootstrap-in-action
### Bootstrap 简介、核心概念
#### Bootstrap是什么
- 基于HTML 、CSS、 JavaScript的前端框架 
- 响应式布局
- 移动设备优先
#### HTML5 doctype

```
	<!DOCTYPE html>
	<html lang="en">
	...
	</html>
```
#### 响应式meta标签
```
<meta name="viewport" content="width=device-width, initial-scale=1">
```
#### Normalize.css
- 使用Normalize来建立跨浏览器的一致性
Normalize.css是一种CSS reset的替代方案。它在默认的HTML元素样式上提供了跨浏览器的高度一致性(实现不同浏览器之间样式的统一)。相比于传统的CSS reset，Normalize.css是一种现代的、为HTML5准备的优质替代方案（https://necolas.github.io/normalize.css/7.0.0/normalize.css）
- Reboot
	Normalize所有的里面之外的元素，Normalize没有定义的样式

#### Bootstrap网格系统
##### 什么是移动设备优先策略呢？
- 基础的CSS是移动优先。优先设计更小的宽度
- 媒体查询。针对于平板电脑、台式电脑
- 渐进增强。随着屏幕大小的增加而添加元素
##### 响应式：viewport尺寸的增加，系统会自动分为最多12列
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191222193530244.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zOTU0MTY1Nw==,size_16,color_FFFFFF,t_70)
##### Bootstrap网格选项
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191222193628634.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zOTU0MTY1Nw==,size_16,color_FFFFFF,t_70)
##### Bootstrap网格示例
- 实例：移动设备和桌面屏幕
```
<!-- Stack the columns on mobile by making one full-width and the other half-width -->
<div class="row">
  <div class="col-xs-12 col-md-8">.col-xs-12 .col-md-8</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>

<!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
<div class="row">
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>

<!-- Columns are always 50% wide, on mobile and desktop -->
<div class="row">
  <div class="col-xs-6">.col-xs-6</div>
  <div class="col-xs-6">.col-xs-6</div>
</div>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191222193936420.png)
- 实例：手机、平板、桌面

```
<div class="row">
  <div class="col-xs-12 col-sm-6 col-md-8">.col-xs-12 .col-sm-6 .col-md-8</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>
<div class="row">
  <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
  <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
  <!-- Optional: clear the XS cols if their content doesn't match in height -->
  <div class="clearfix visible-xs-block"></div>
  <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
</div>
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191222194032783.png)
##### Bootstrap 常用组件、样式
- Typography
- Table
- Form
- Button
- Dropdown
- Button Group
- Input Group
- Navbar
- Pagination
- Tag
- Alert
- Modal Dialog
- Progress Bar
- List Group
- Card
- Tooltip
### Spring Boot +Thymeleaf + Bootstrap实战
![在这里插入图片描述](https://img-blog.csdnimg.cn/20191222212733542.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl8zOTU0MTY1Nw==,size_16,color_FFFFFF,t_70)

github:
https://github.com/gitAxin/bootstrap-in-action.git
