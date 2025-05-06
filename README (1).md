
# 兔鲜商城

本项目是一款基于 uniapp 构建的商城应用，涵盖了模拟微信登录、商品列表展示、商品详情展示、订单状态修改等核心功能模块。借助 uniapp 的跨平台特性，可以在多个终端上运行，为用户提供高效便捷的购物体验。

## 技术栈

Vue 3，TypeScript，Vue Router，Pinia，Axios，uniapp，uni-ui，ESLint

## Windows系统环境搭建步骤

* 安装node.js(16+)
* 安装pnpm，控制台输出npm install -g pnpm
* 再输出pnpm install
* 将代码编译为微信小程序代码，pnpm dev:mp-weixin
* 将编译完的dist->dev->mp-weixin文件夹导入微信开发者工具即可