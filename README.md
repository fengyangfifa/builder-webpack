# 构建包功能设计-基于webpack4



## 基础配置 webpack.base.js

### 资源解析

> 解析 ES6
>
> 解析 React
>
> 解析 CSS
>
> 解析 Less
>
> 解析图片
>
> 解析字体

### 样式增强

> CSS 前缀补齐
>
> CSS px 转换成 rem

### 目录清理

### 多页面打包

### 命令行信息显示优化

### 错误捕获隔和处理

### CSS提取成一个单独文件



## 开发阶段配置 webpack.dev.js

### 代码热更新

> CSS 热更新
>
> JS 热更新

### source map



## 生产阶段配置 webpack.prod.js

### 代码压缩

### 文件指纹

### Tree Shaking

### Scope Hoisting

### 速度优化

> 基础包 CDN

### 体积优化

> 代码分割



## SSR 配置 webpack.ssr.js

### output 的 libraryTarget 配置

### CSS 解析 ignore



