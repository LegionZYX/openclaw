# OpenClaw 中国版 - 真实技能清单

## 📦 实际包含的内容

### 1. 官方 Bundled Skills (55个)

这些都是 OpenClaw 官方仓库自带的真实技能：

| 分类 | 技能 | 描述 |
|------|------|------|
| **AI 模型** | gemini | Google Gemini CLI |
| | nano-banana-pro | Gemini 图像生成 |
| | openai-image-gen | OpenAI 图像生成 |
| | openai-whisper | OpenAI 语音识别（本地） |
| | openai-whisper-api | OpenAI 语音识别（API） |
| **开发工具** | github | GitHub CLI 操作 |
| | gh-issues | GitHub Issues 自动化 |
| | coding-agent | 代码生成代理 |
| | skill-creator | 技能创建工具 |
| **通讯平台** | discord | Discord 集成 |
| | slack | Slack 集成 |
| | bluebubbles | iMessage (BlueBubbles) |
| | imsg | iMessage (直接) |
| **笔记应用** | notion | Notion 集成 |
| | obsidian | Obsidian 集成 |
| | bear-notes | Bear 笔记 |
| | apple-notes | Apple 备忘录 |
| **任务管理** | apple-reminders | Apple 提醒事项 |
| | things-mac | Things 3 |
| | trello | Trello 看板 |
| **媒体工具** | canvas | Canvas 可视化 |
| | camsnap | 摄像头截图 |
| | video-frames | 视频帧提取 |
| | spotify-player | Spotify 播放器 |
| **实用工具** | 1password | 1Password 集成 |
| | weather | 天气查询 |
| | summarize | 文本摘要 |
| | healthcheck | 健康检查 |
| **其他** | clawhub | ClawHub 技能市场 |
| | mcporter | MCP 工具 |
| | tmux | Tmux 集成 |
| | ... | (共55个) |

### 2. 飞书完整集成 (extensions/feishu/)

| 技能 | 描述 | 状态 |
|------|------|------|
| feishu-calendar | 飞书日历 | ✅ 完整实现 |
| feishu-bitable | 飞书多维表格 | ✅ 完整实现 |
| feishu-task | 飞书任务 | ✅ 完整实现 |
| feishu-im-read | 飞书消息读取 | ✅ 完整实现 |
| feishu-doc | 飞书文档 | ✅ 完整实现 |
| feishu-drive | 飞书云盘 | ✅ 完整实现 |
| feishu-wiki | 飞书知识库 | ✅ 完整实现 |
| feishu-perm | 飞书权限 | ✅ 完整实现 |

### 3. 中国技能包 (skills/office/)

| 技能 | 描述 | 来源 |
|------|------|------|
| lark-calendar | 飞书日历管理 | skill-marketplace |

---

## 🚫 关于 skill-marketplace 的说明

`skill-marketplace` 项目中的 53 个"中国商业技能"**不是真实的技能文件**，它们只是：

- JSON 数据定义
- 概念性的技能列表
- 没有实际的 SKILL.md 文件
- 大部分 ClawHub 链接不存在

**真实可用的技能只有：**
1. OpenClaw 官方 bundled skills (55个)
2. 飞书插件完整集成 (8个)
3. skill-marketplace 中的 1 个示例 (lark-calendar)

---

## 🔍 如何查找真实技能

### 方式 1: ClawHub 官方市场

```bash
# 访问 ClawHub
https://clawdhub.com

# 或使用命令
openclaw clawhub list
```

### 方式 2: 本地已安装技能

```bash
# 查看本地技能
ls ~/.agents/skills/
ls ~/.openclaw/extensions/*/skills/
```

### 方式 3: OpenClaw 官方仓库

```bash
# 官方技能仓库
https://github.com/openclaw/skills
```

---

## 📚 相关链接

- **OpenClaw 中国版**: https://github.com/LegionZYX/openclaw
- **OpenClaw 官方**: https://github.com/openclaw/openclaw
- **ClawHub 技能市场**: https://clawdhub.com
- **OpenClaw 文档**: https://docs.openclaw.ai
- **社区 Discord**: https://discord.gg/clawd

---

**生成时间**: 2026-03-10
**版本**: v2026.3.10-cn.1

**重要**: 这是一个诚实的清单，只列出真实存在的内容。不包含虚构的技能。
