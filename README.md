# Zhang-LXuan Skills

OpenClaw 自动化工具集，包含自用技能和配置。

## 📦 Skills

### qq-email-watcher
QQ 邮箱监控通知，支持 AI 智能摘要、验证码/关键信息高亮、白名单过滤。

**功能：**
- 🔍 IMAP 轮询（每 30 秒检查新邮件）
- 🤖 AI 智能摘要（提炼验证码、金额、链接等关键信息）
- ✂️ 智能预览（短邮件展示全文，长邮件 AI 总结）
- 🔒 去重机制（首次运行自动初始化，重启不重复通知）

**快速安装：**
```bash
npx clawhub@latest install qq-email-watcher
```

---

### ordercli
Foodora/Deliveroo 订单查询 CLI（仅支持 Foodora）。

**安装：**
```bash
brew install steipete/tap/ordercli
# 或
go install github.com/steipete/ordercli/cmd/ordercli@latest
```

---

### tencent-channel-community
腾讯频道（QQ 频道）管理工具，支持频道、帖子、成员、日程等管理。

---

### skill-finder-cn
中文技能市场搜索工具，搜索 ClawHub 上的中文可用技能。

---

### vision-analysis
图像分析工具，基于 MiniMax Vision API，支持图像描述、OCR、图表提取等。

---

## 🔧 通用配置

### 安装 Skill
```bash
npx clawhub@latest install <skill-name>
```

### 查看已安装 Skills
```bash
openclaw skills list
```

更多技能：https://clawhub.ai/Zhang-LXuan

## 📁 目录结构

```
skills/
├── qq-email-watcher/         # QQ 邮箱监控
├── ordercli/                 # 外卖订单查询
├── tencent-channel-community/ # 腾讯频道管理
├── skill-finder-cn/          # 中文技能搜索
└── vision-analysis/          # 图像分析
```

## 🤖 关于 OpenClaw

OpenClaw 是一个 AI 助手框架，支持多渠道（QQ、Telegram、Discord 等）、多技能、自定义工具。

官网：https://openclaw.ai
文档：https://docs.openclaw.ai
