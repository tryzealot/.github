# Zealot

[![GitHub release](https://img.shields.io/github/v/release/tryzealot/zealot?include_prereleases)](https://github.com/tryzealot/zealot/blob/develop/CHANGELOG.md)
[![Docker Pulls](https://img.shields.io/docker/pulls/tryzealot/zealot.svg)](https://hub.docker.com/r/tryzealot/zealot/)
[![Maintainability](https://codeclimate.com/github/tryzealot/zealot/badges/gpa.svg)](https://codeclimate.com/github/tryzealot/zealot)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5e5c7bbeb1214fa39b11a7414f0d7171)](https://www.codacy.com/gh/tryzealot/zealot)
[![License](https://img.shields.io/github/license/tryzealot/zealot)](LICENSE)

[English Document](https://zealot.ews.im/#/en/) | [简体中文文档](https://zealot.ews.im)

开源自部署 iOS、Android 及 macOS 应用分发平台，提供 iOS、Android SDK、fastlane 等丰富组件库，打包分发流程、上传应用竟然如此简单、独立部署解决企业使用的烦恼。 En Taro Adun! 🖖

![Zealot Showcase](https://zealot.ews.im/_media/showcase.png)
## 特性

- [x] 支持 iOS、Android (apk/aab) 和 macOS 应用的上传、在线安装和本地下载
- [x] 支持创建类型（Debug、AdHoc、Release）及渠道（小米商店等）
- [x] 支持自定义网络钩子通知各种服务（钉钉、企业微信、Slack 等）
- [x] 支持 iOS dSYM 和 Android Progruard 文件的解析和上传
- [x] 支持应用解包（甚至 mobileprovision 文件）存储和分享
- [x] 支持一键登录（已接入飞书、Gitlab、Google 和 LDAP）
- [x] 提供检查新版本和安装服务的 iOS 和 Android 组件
- [x] 提供获取 iOS 设备标识符并显示支持安装的应用列表
- [x] 提供丰富的 fastlane 插件 [zealot](https://github.com/tryzealot/fastlane-plugin-zealot)
- [x] 可接入 Gitlab 服务直接挂钩源码管理
- [ ] 可接入 Jenkins 服务实现远程构建
- [x] 支持丰富的 REST APIs
- [ ] 支持 GraphQL 接口（进行中）

## 在线演示

- 演示地址：https://tryzealot.herokuapp.com/
- 电子邮箱: `admin@zealot.com`
- 登录密码：`ze@l0t`

> **注意**: 数据每日都会重新初始化，不对用户上传的应用承担任何法律风险，后果自负！
