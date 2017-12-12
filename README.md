# GRID 布局

主要定义了网格的列和行，可用于css中复杂的定位的实现。

### 基础实现
````
1. 在父元素上声明 display: grid;使子元素全部变为网格项目。
2. 在父元素上可通过grid-template-columns 和 grid-template-rows属性确定网格中的行和列，定义轨道。
通过grid-gap来定义间隙。
````

### 记录

````

1. grid与flex布局相似，可配合使用
2. 兼容至ie11
3. fr单位的应用场景
4. grid-column:1/3 代表 {grid-column-start:1; grid-column-end:3;}网格线的1~3

````

### demo
[https://chenluily0451.github.io/grid/](https://chenluily0451.github.io/grid/)

### 待续
