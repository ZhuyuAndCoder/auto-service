---
支持数组型remoteurl满足项目需求
name: 指南
route: /
---

import logo from './public/assets/logo.png';
import swagger from './public/assets/swagger.png';

# Autos

## 介绍

Autos（automatic Service），根据 [Swagger](https://swagger.io/) 或者 [YApi](https://github.com/YMFE/yapi) 格式的接口文档（JSON）自动生成 TypeScript 的接口调用或者类型代码。

Autos 依赖基于开源项目 [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) 定制开发的 Java [生成工具](https://github.com/gogoyqj/swagger-codegen)，请确保您的平台已经安装 Java。

## 特性

- 支持 Swagger 和 YApi 两种格式的接口文档
- 支持[增量更新](/auto-service/getting-started#3-增量更新)接口文档数据
- 支持对[接口规范性](https://mp.weixin.qq.com/s?__biz=MzI3NDk1MzE4NA==&mid=2247483733&idx=1&sn=0fd7e35f17f47034ed42b023419482e9&chksm=eb0d67dadc7aeeccf56b34074764360c5d2525bf1f943f83205bfa2e92ec343e79fd44c01877&token=824089189&lang=zh_CN#rd)进行检查
- 支持仅生成 TypeScript 类型代码
- 支持所有 [Swagger Codegen](/auto-service/getting-started#112-swaggerparser) 的特性，包括自定义 TypeScript 代码模板
- 支持对接口入参、数据返回进行[校验](/auto-service/service-validate)

## Autos 是如何工作的？

<img src={swagger} style={{ width: 800 }} />

## 命名由来

Autos 曾经有一个不那么酷的名字 “sm2tsservice”（Swagger or Mock to TypeScript Service）。

换成 “ Autos”（automatic Service） 从字面上能更好被理解、更容易被记住，logo 则蹭一下变形金刚的名气，采用的是 “Autobot(s)” （博派）的标志。

<img src={logo} style={{ width: 160 }} />
