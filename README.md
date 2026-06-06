# DxmTemuTerminalRobot 运行包

这个目录是机器人可执行运行包，主要入口是：

```text
DxmTemuTerminalRobot.exe
```

首次运行后程序会在 `work` 下自动生成本机运行数据。

## Git 上传策略

已排除以下本机数据，避免把账号登录态、API Key、飞书 Webhook、运行日志和图片缓存提交到仓库：

- `work/chrome-profile/`
- `work/state/`
- `work/logs/`
- `work/downloads/`

如果需要迁移配置，请在目标电脑上重新打开程序填写并保存配置。
