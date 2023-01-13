---
title: 什么是Packagist Mirrors
---

## 什么是Composer
 Composer是PHP中的依赖管理工具。您可以在自己项目中声明自己的依赖，并管理(安装/更新/删除)他
## 什么是Packagist
  Packagist是Composer的官方依赖库，它提供了一个在线的依赖库，您可以在这里找到您需要的依赖
## 什么是Packagist Mirrors
  Packagist Mirrors是一个开源的项目。您可以使用它来搭建自己的Packagist镜像站，或者使用我们提供的镜像站。
  我们的镜像站提供了更快的同步速度和更快的下载速度。
## 特性

- 60s极速同步，满足大家需求
- 全量镜像同步
- 遍布全球的CDN节点加速
- 服务状态检测，保证故障第一时间处理

## 如何使用
### 全局生效
```bash
composer config -g repo.packagist composer https://repo.packagist.cloud
```

### 项目生效
```bash
composer config repo.packagist composer https://repo.packagist.cloud
```

## 如何取消
### 全局
```bash
composer config -g --unset repos.packagist
```
### 项目
```bash
composer config --unset repos.packagist
```

## 问题反馈
请联系邮箱 i#nxx.email


