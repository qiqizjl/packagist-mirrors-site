---
hero:
  title: Packagist
  description: 可能是国内同步最快的Packagist镜像站

features:
  - title: 更快的同步速度
    emoji: 💎
    description: 官方数据更新后1分钟内完成同步
  - title: 更快的下载速度
    emoji: 🌈
    description: 使用融合CDN为镜像站提供下载加速
  - title: '更全的镜像内容'
    emoji: 🚀
    description: 全量同步所有文件，保证Composer里的所有文件均可以通过镜像站下载
---

## 方法

### 全局生效

```bash
composer config -g repo.packagist composer https://repo.packagist.cloud
```

### 项目生效

```bash
composer config repo.packagist composer https://repo.packagist.cloud
```
