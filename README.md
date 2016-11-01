# 一个抽离出bootstrap的浮动 ge栅栏格系统
#### 简介
大部分前端人员在快速开发原型的时候 喜欢用bootstrap的栅栏格来布局，但是往往引入N多不太有用的东西
所以 花了十五分钟 仿照bootstrap的栅栏格 抽离仿写了一个栅栏格系统 基于浮动 兼容ie8
#### 用法
```html
 <div class="g-container ">
  <div class="row">
  <!--宽度为百分比-->
  <div class="g05">5</div>
  <div class="g10">10</div>
  <div class="g15">15</div>
  <div class="g20">20</div>
  <div class="g25">25</div>
  <div class="g" style="with:17%">特殊情况的长度</div>
  </div>
</div>
```
