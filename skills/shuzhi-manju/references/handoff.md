# Handoff

## When To Package

打包给新会话或另一个 Agent：

- 当前会话变卡。
- 还有大量 Board 未生成。
- 用户希望多 Agent 接力。
- 需要人工网页端继续提交。

## Required Contents

```text
HANDOFF_README.md
images/Board_XX.png ...
prompts/Board_XX.txt ...
continuity/START_FRAME_FOR_BOARD_XX.png
audio/voice_reference.m4a
reference_docs/
```

## Handoff README Must Include

- 已完成到第几条。
- 下一条从哪个 Board 开始。
- 当前使用模型、分辨率、画幅、时长。
- 是否禁止高消耗模式。
- 第一张参考图是什么。
- 第二张参考图规则。
- 音频参考规则。
- 单并发要求。
- 下一条提示词是否已按真实尾帧改过。

## Sanitization Rules

开源或交接给外部时去掉：

- 个人本地路径。
- 账号、资源标识、任务标识、任务日志。
- 未授权素材、未公开项目文件。
- 费用记录和队列记录。
- 与通用方法无关的具体项目名。
