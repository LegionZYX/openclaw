---
name: report-generator
description: 自动生成业务报表,支持多种格式
metadata:
  openclaw:
    emoji: 📊
    category: data
    requires:
      apis: []
      bins: []
    always: true
---

# 报表生成器

自动生成各类业务报表，支持 Excel、PDF、HTML 等格式。

## 功能

- 📊 多种报表类型（销售、财务、运营等）
- 📈 数据可视化
- 📅 定期自动生成
- 📧 邮件发送
- 💾 多种格式导出

## 使用场景

### 1. 生成销售报表

**用户**: "生成本月销售报表"

**Agent**:
```
正在生成报表...

✅ 销售报表已生成:

## 2026年3月销售报表

### 概览
- 总销售额: ¥1,234,567
- 订单数: 1,234
- 客单价: ¥1,000
- 环比增长: +15.3%

📊 完整报表已保存至: /reports/2026-03-sales.xlsx
```

## 配置

无需配置，开箱即用。
