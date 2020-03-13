# domes

> A Vue.js project 项目描述

``` bash
# 跑环境
npm install
# 跑项目
npm run dev
# 打包文件
npm run build
```
项目目录介绍：
 主要目录
 |- src
      |- assets ：公共的css文件，js文件
      |- components:组件文件
         |- home ：首页模块
         |- list ：列表模块
         ...
         |- base ：公共组件
         |-router ：路由管理
         |-store  ：数据状态管理 
            |- index.js 核心状态 只放首页状态
            |- list.js  列表模块状态
            ....
      |- main.js 入口js文件

 |- index.html 入口html文件

添加公共导航：src->base->navlist中添加
添加公共插件：。。。。

    
