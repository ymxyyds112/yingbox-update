# 影视box 在线升级源

- 当前版本：v2.4.44（versionCode 20444）
- 更新时间：2026-11-05

## 手机版配置（手机 / 平板 App）

工具栏「在线升级」→ ⚙ 手动输入服务器地址 → 填：

```
https://gh-proxy.org/https://raw.githubusercontent.com/ymxyyds112/yingbox-update/main
```

## 文件说明

| 路径 | 用途 |
|---|---|
| `api/mobile/version` | **手机版独立通道**，App 实际请求 `{服务器地址}/api/mobile/version` |
| `version.json` | 主通道副本，备用入口 |
| Release `latest` / `yingbox-latest.apk` | APK 本体，固定 tag 保证下载链接永久不变 |

> 手机/平板端与电视端功能不同，分属独立升级通道，互不干扰。手机端只维护 api/mobile/version。
