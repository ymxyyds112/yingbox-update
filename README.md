# 影视box 在线升级源（仅手机 / 平板端）

- 当前版本：v2.4.49（versionCode 20449）
- 更新时间：2026-11-07

## 服务器地址（所有版本通用）

工具栏「在线升级」→ ⚙ 手动输入服务器地址 → 填：

```
https://gh-proxy.org/https://raw.githubusercontent.com/ymxyyds112/yingbox-update/main
```

v2.4.29 等老版本同样填这一个地址，会直接检查到 v2.4.49 并升级，
无需专用地址、无需一版一版升。

## 文件说明

| 路径 | 用途 |
|---|---|
| `api/mobile/version` | v2.4.36 及以后读取的版本文件 |
| `api/app/version` | v2.4.35 及更早读取的版本文件（内容与上面完全相同） |
| `version.json` | 主通道副本，备用入口 |
| Release `latest` / `yingbox-latest.apk` | APK 本体，固定 tag 保证下载链接永久不变 |

> 电视端已放弃、不走在线更新；本仓库全部通道只服务手机 / 平板 App。

