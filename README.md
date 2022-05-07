# 安装使用

项目只用到了 node-sass 这一个 dev-dependency

```js
// 安装项目的依赖node-sass
npm i
// 打开 index.html 即可
```

# 项目说明

这个项目是用来学 grid 布局和 sass 的

根据页面布局，分开管理 css 文件，再统一导入到 main.scss 文件中。  
sass 的文件管理：  
\_base 👉 存放 sass 变量、样式重置  
\_typography 👉 存放字体样式  
footer、header、gallery 等其余各个部分，分别对应各自的页面结构
