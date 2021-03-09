## VUE-H5-TEMPLATE

<p>
  <a href="https://github.com/vuejs/vue">
    <img src="https://img.shields.io/badge/vue-2.6.11-brightgreen.svg" alt="vue">
  </a>
  </a>
    <a href="https://youzan.github.io/vant/#/zh-CN/">
    <img src="https://img.shields.io/badge/vant-2.7.0-brightgreen.svg" alt="vant">
  </a>
  <a href="https://www.npmjs.com/">
    <img src="https://img.shields.io/badge/npm-6.9.0-blue.svg" alt="npm">
  </a>
  <a href="https://github.com/Ewall1106/panda-vue-template/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="license">
  </a>
</p>

`Vue-H5-Template` 项目以小商城作为基本的内容演示，使用 `Vue3.0+Typescript+Vant` 搭建 `移动端h5页面` 开发所需的基础模板，并提供一些通用型的解决方案及扩展功能。

## 基本说明

- [文档说明](https://docs.xwhx.top/mall)
- [接口文档](https://yapi.xwhx.top)
- [电脑预览](https://mall.xwhx.top)
- [更新日志](https://github.com/Ewall1106/mall/blob/master/changelog.md)

### 部分页面预览：

|                                首页                                 |                                商详                                 |                               购物车                                |                                我的                                 |
| :-----------------------------------------------------------------: | :-----------------------------------------------------------------: | :-----------------------------------------------------------------: | :-----------------------------------------------------------------: |
| <img width="200" src="https://s3.ax1x.com/2021/01/06/sVDeFs.jpg" /> | <img width="200" src="https://s3.ax1x.com/2021/01/06/sV06De.jpg" /> | <img width="200" src="https://s3.ax1x.com/2021/01/06/sV0yuD.jpg" /> | <img width="200" src="https://s3.ax1x.com/2021/01/06/sV0rjO.jpg" /> |

### 手机扫码预览：

<img width="200" class="zoom" src="https://s3.ax1x.com/2021/01/06/sVDlOU.png">

## 安装使用

```bash
# 项目下载
# 克隆项目很慢？将地址中的 `github.com` 替换为 `github.com.cnpmjs.org` 试试
$ git clone git@github.com:Ewall1106/mall.git

# 安装运行
$ npm install
$ npm run dev
```

## 功能特性

:hammer: 开发规范

- `Eslint` 校检及错误提示
- `Prettier` 统一代码风格

:hammer: 初始化配置

- vw 移动端适配
- css 预处理器
- 浏览器默认样式处理
- promise 降级
- fast-click 处理

:hammer: 基础功能

- 路由配置及权限控制
- axios 封装及请求

## 目录结构

```bash
|-- public                // public
|-- src
|   |-- api               // 接口列表
|   |-- assets            // 图片资源
|   |-- components        // 公共组件
|   |-- icons             // svg图标
|   |-- router            // 路由
|   |-- store             // vuex
|   |-- styles            // 公共样式
|   |-- utils             // 工具函数
|   |-- views             // 具体页面
|   |-- App.vue           // 主页面
|   |-- main.js           // 入口文件
|   |-- permission.js     // 权限控制逻辑
|-- package.json          // 客户端依赖
|-- .eslint.xx            // eslint处理
|-- babel.config.js       // babel配置文件
|-- postcss.config.js     // postcss配置文件
|-- vue.config.js         // vue相关配置文件
|-- ...
```

:bookmark: 目录说明：

- 目录 `components` 下的所有公共组件使用 [tsx](https://v3.vuejs.org/guide/render-function.html) 进行开发。
- 目录 `views` 下的业务组件使用 [sfc](https://cn.vuejs.org/v2/guide/single-file-components.html) 的形式进行开发。
- 为什么这样划分？对于公共组件来说，使用 `tsx` 开发更加灵活、渲染性能更好且更方便测试。对于业务组件，使用 `sfc` 的方式可以更好的发挥出 `vue` 的优势，简洁明了。

## 协议

- [MIT](https://github.com/Ewall1106/mall/blob/master/LICENSE)

- Copyright (c) 2021-present Ewall&熊猫