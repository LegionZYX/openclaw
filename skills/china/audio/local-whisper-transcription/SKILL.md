---
name: local-whisper-transcription
description: 完全离线的高质量语音识别
metadata:
  openclaw:
    emoji: 🎤
    category: audio
    requires:
      apis: []
      bins: ["whisper"]
    install:
      - id: pip
        kind: pip
        formula: "openai-whisper"
        bins: ["whisper"]
        label: "Install Whisper (pip)"
---

# 本地Whisper转录

使用 OpenAI Whisper 模型进行完全离线的高质量语音识别。

## 功能

- 🎤 高质量语音识别
- 🔒 完全离线运行
- 🌐 多语言支持
- 📝 自动标点和分段
- 💾 多种格式输出

## 使用场景

### 1. 转录会议录音

**用户**: "转录这个会议录音文件"

**Agent**:
```
正在处理音频文件...

🎤 Whisper 转录中:
- 模型: base
- 语言: 中文
- 时长: 45:23

✅ 转录完成:

## 会议转录

**时间**: 2026-03-10 14:00-14:45
**参会人**: 张三、李四、王五

---

### 议题1: Q2产品规划
**张三**: 我们Q2的主要目标是完成会员系统的开发...

📁 保存位置: /transcripts/meeting-20260310.txt
```

## 配置

### 环境变量

```bash
WHISPER_MODEL=base
WHISPER_LANGUAGE=auto
```
