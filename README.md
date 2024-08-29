# 辽源山海-云端养殖购物小程序

## 项目概述

辽源山海-云端养殖购物小程序是一款基于微信平台的小程序,旨在推广辽宁的山参和海参产品,并提供云养殖和云购物的功能。通过该小程序,用户可以了解山参和海参的种植/养殖情况、购买相关产品,同时还可以体验远程参与养殖的乐趣。

## 项目目标

- 推广辽宁的山参和海参产品
- 增加产品的知名度和销售量
- 提供云养殖和云购物功能
- 让用户了解产品的生产过程
- 提供便捷的购物体验

## 主要功能

1. 用户管理：注册、登录、个人信息管理
2. 山参种植：领水、浇水、施肥、采摘等操作
3. 海参养殖：投放幼苗、投喂、捕获等操作
4. 商品浏览：商品展示、搜索、加入购物车
5. 购物车：添加、删除商品,结算
6. 订单管理：下单、支付、查看订单
7. 系统管理：用户权限管理、数据维护等

## 技术架构
使用JavaScript + WXSS + ESLint进行构建
项目结构如下
```
|-- LIAOYUAN
    |-- README.md
    |-- app.js
    |-- app.json
    |-- app.wxss
    |-- components    //    公共组件库
    |-- config    //    基础配置
    |-- custom-tab-bar    //    自定义 tabbar
    |-- model    //    mock 数据
    |-- pages
    |   |-- cart    //    购物车相关页面
    |   |-- coupon    //    优惠券相关页面
    |   |-- goods    //    商品相关页面
    |   |-- home    //    首页
    |   |-- order    //    订单售后相关页面
    |   |-- promotion-detail    //    营销活动页面
    |   |-- usercenter    //    个人中心及收货地址相关页面
    |   |-- ginseng-cultivation    //    山参种植页面
    |   |-- sea-cucumber-cultivation    //    海参种植页面
    |-- services    //    请求接口
    |-- style    //    公共样式与iconfont
    |-- utils    //    工具库
```
## 数据模拟
采用真实的接口数据，模拟后端返回逻辑，在小程序展示完整的云养殖场景与购物体验逻辑。
## 贡献指南

我们欢迎并感谢任何形式的贡献。如果您想为这个项目做出贡献,请遵循以下步骤:

1. Fork 这个仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request
