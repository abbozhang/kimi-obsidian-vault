# Obsidian Vault

我的 Obsidian 知识库，由 Kimi (Claw) 协助管理。

## 用途

- 📝 每日工作、生活、AI 新闻日志
- 💡 灵感收集与材料整理
- 🧠 知识沉淀与周报管理
- 🗂️ 笔记索引与导航

## 结构

```
obsidian-vault/
├── 📄 核心配置文件（根目录）
│   ├── SOUL.md         # AI 助手的核心价值观和行为准则
│   ├── USER.md         # 用户信息和偏好
│   ├── AGENTS.md       # Agent 配置
│   ├── TOOLS.md        # 工具集成
│   ├── BOOTSTRAP.md    # 启动配置
│   └── IDENTITY.md     # 身份识别
├── 📓 Daily/          # 每日笔记（工作、生活、Claw日志、AI新闻）
├── 📥 Inbox/          # 灵感收件箱和外部材料
│   ├── 一些AI需求.md
│   └── 材料/          # 来自小宇宙、小红书等的长文材料
├── 🧠 Knowledge/      # 整理后的知识库
│   └── 周报/          # 工作周报、生活周报（每周六自动生成）
├── 🗂️ MOC/            # Map of Content（内容索引）
│   ├── 日记索引.md
│   └── 灵感索引.md
├── 📋 _config/        # 系统配置和规则文档
│   ├── 笔记写入规则.md
│   ├── 红线准则.md
│   ├── 定时任务.md
│   ├── git-config.md
│   ├── KimiVault-Structure.md
│   └── archive/       # 历史备份文件
└── 🔧 skills/         # Obsidian 操作技能脚本
```

## 自动化任务

- 🌅 **每天 08:00**：自动抓取 AI 界大事记
- 🌙 **每天 23:50**：自动记录 Claw 工作日志
- 📊 **每周六 08:00**：自动生成工作周报和生活周报

详见 `_config/定时任务.md`

## 笔记规则

详见 `_config/笔记写入规则.md` 和 `_config/红线准则.md`

## 同步

此仓库通过 Git 自动同步到 MacBook 本地 Obsidian。
