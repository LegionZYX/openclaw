# 🦞 OpenClaw 中国版

> 🇨🇳 内置中国商业场景技能的开箱即用版本

## ✨ 特性

**OpenClaw 中国版** 在官方版本基础上，内置了 **5+ 个开箱即用的中文技能**：

| 分类 | 技能 | 描述 |
|------|------|------|
| 📝 内容创作 | content-creator | AI辅助内容创作 |
| 💬 客户服务 | smart-customer-service | 智能客服系统 |
| 📊 数据分析 | report-generator | 报表生成器 |
| 🛒 电商运营 | inventory-manager | 库存管理 |
| 🎤 语音处理 | local-whisper-transcription | 本地语音识别 |

## 🚀 快速开始

```bash
# 安装依赖
pnpm install

# 构建
pnpm build

# 运行
pnpm openclaw onboard
```

## 📖 技能使用

### 内容创作

```
你: 帮我写一段营销文案

AI: ✨ 产品营销文案:

## [产品名称] - 重新定义你的工作方式
...
```

### 智能客服

```
你: 客户问：退货政策是什么？

AI: ✅ 智能回复:
感谢您的咨询！我们的退货政策如下...
```

## 🏗️ 项目结构

```
openclaw-china/
├── skills/
│   └── china/           # 🇨🇳 中国商业技能
│       ├── content/     # 内容创作
│       ├── service/     # 客户服务
│       ├── data/        # 数据分析
│       ├── ecommerce/   # 电商运营
│       └── audio/       # 语音处理
└── extensions/
    └── feishu/          # 飞书完整集成
```

## 📄 许可证

MIT License
