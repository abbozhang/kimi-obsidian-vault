# README.md

欢迎来到 **Abbo 的 Obsidian Vault** 🧠

这是一个由 Kimi AI 协助管理的个人知识库，专注于AI领域学习、产品思考和日常记录。

---

## 📂 文件结构

```
obsidian-vault/
├── Daily/              # 每日日记（YYYY-MM-DD.md）
├── Inbox/              # 临时收集箱，存放未整理的想法
├── Knowledge/          # 永久知识库
│   ├── 周报/           # 每周工作和生活总结
│   ├── 参考材料/       # 访谈、文章等参考内容
│   └── AI需求清单.md   # AI产品想法和需求
├── MOC/                # Map of Content，内容索引
│   ├── 日记索引.md
│   └── 灵感索引.md
├── _config/            # 系统配置文档
│   ├── 智能写入系统.md
│   ├── 定时任务.md
│   ├── 笔记写入规则.md
│   ├── 红线准则.md
│   └── archive/        # 归档的旧文档
├── skills/             # 自动化脚本
└── 系统文件            # SOUL.md, USER.md, AGENTS.md等
```

---

## 🤖 Kimi AI 协助系统

### 智能写入
当你在聊天窗口发送内容时，Kimi会自动：
1. 识别内容类型（日记、知识笔记、灵感等）
2. 写入到正确的文件和位置
3. 提交并推送到GitHub

详见：[智能写入系统](_config/智能写入系统.md)

### 定时任务
- **每天08:00：** 收集昨天的AI行业大事记
- **每天23:50：** Kimi总结当天工作日志
- **每周六08:00：** 生成工作周报和生活周报

详见：[定时任务](_config/定时任务.md)

---

## 🎯 使用方式

### 本地（MacBook）
```bash
cd ~/path/to/obsidian-vault
git pull origin main  # 同步最新内容
```

在Obsidian中正常使用，修改后：
```bash
git add -A
git commit -m "描述"
git push origin main
```

### 通过Kimi
直接在聊天窗口发送内容，例如：
- "今天见了张三讨论项目" → 自动写入Daily
- "学习了Python异步编程" → 自动写入Knowledge
- "突然想到一个产品功能" → 自动写入Inbox

---

## 📊 统计信息

- **创建日期：** 2026年初
- **总笔记数：** 28+ 篇
- **最近更新：** 2026-02-23
- **Git提交数：** 持续增长中

---

## 🔗 相关链接

- **GitHub仓库：** [abbozhang/kimi-obsidian-vault](https://github.com/abbozhang/kimi-obsidian-vault)
- **Obsidian官网：** [obsidian.md](https://obsidian.md)

---

## 📝 更新日志

### 2026-02-23
- ✅ 重构文件夹结构，合并重复目录
- ✅ 配置智能写入系统
- ✅ 创建三个核心定时任务
- ✅ 整理Inbox内容到Knowledge
- ✅ 完善系统配置文档

---

_由 Kimi AI 维护，持续进化中_ 🚀