# 树枝漫剧 Skill

树枝漫剧是一套用于中文 AI 漫剧、科幻科普短片、连续分镜视频的 Codex Skill。

它专注于四件事：

- 把长文案拆成连续的 15 秒视频 Board。
- 为每个 Board 生成可执行的影视化提示词。
- 用上一段真实尾帧承接下一段首帧，保持视频连续。
- 在长队列中保留声线、画风、运镜和交接规范。

## 安装

将 `skills/shuzhi-manju` 复制到 Codex skills 目录：

```powershell
Copy-Item -Recurse -Force ".\skills\shuzhi-manju" "$env:USERPROFILE\.codex\skills\shuzhi-manju"
```

## 使用示例

- 使用树枝漫剧 Skill，把这篇文案拆成 15 秒连续分镜。
- 按树枝漫剧流程，生成 Seedance/Jimeng 可提交提示词。
- 根据上一条真实尾帧，改写下一条视频开头桥接。
- 把剩余 Board 打包成接力说明给另一个 Agent。

## 脱敏说明

本仓库只包含通用 Skill 方法，不包含任何个人路径、账号、项目素材、生成记录、平台资源标识、任务标识、具体费用记录或未公开脚本资产。

## License

See `LICENSE`.
