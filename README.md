# 影视box 在线升级源

- 当前版本：v2.4.27（versionCode 20427）
- 更新时间：2026-11-01

## 电视端配置

工具栏「在线升级」→ ⚙ 手动输入服务器地址 → 填：

```
https://gh-proxy.com/https://raw.githubusercontent.com/ymxyyds112/yingbox-update/main
```

## 文件说明

| 路径 | 用途 |
|---|---|
| `api/app/version` | App 实际请求的版本文件（`{服务器地址}/api/app/version`） |
| `version.json` | 同上，备用入口 |
| Release `latest` / `yingbox-latest.apk` | APK 本体，固定 tag 保证下载链接永久不变 |
