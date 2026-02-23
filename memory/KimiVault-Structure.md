# 🌙 Kimi Claw 的 Vault 结构

> 为每日笔记和灵感记录设计

## 文件夹结构

```
KimiVault/
├── 📓 Daily/                    # 每日笔记（自动归档）
│   ├── 2025-02-22.md
│   ├── 2025-02-21.md
│   └── ...
│
├── 💡 Inbox/                    # 灵感捕获（临时存放）
│   └── 未整理的灵感.md
│
├── 🌱 Fleeting/                 # 闪念笔记（随时记录，定期清理）
│   ├── 随想-20250222-1659.md
│   └── ...
│
├── 🏷️ MOC/                      # Map of Content（索引页）
│   ├── 日记索引.md
│   ├── 灵感索引.md
│   └── 项目索引.md
│
├── 📁 Projects/                 # 具体项目笔记
│   └── （按需创建）
│
├── 📚 Reading/                  # 阅读笔记
│   └── （书籍、文章摘录）
│
└── 🖼️ Attachments/              # 图片、附件
```

## 命名规则

- **每日笔记**: `YYYY-MM-DD.md`
- **闪念笔记**: `随想-YYYYMMDD-HHMM.md`
- **项目笔记**: 使用动词开头，如 `搭建个人博客.md`

## 快速操作

```bash
# 创建今日日记
obsidian-cli create "Daily/$(date +%Y-%m-%d)" --content "# $(date +%Y-%m-%d)\n\n## 今日\n\n- \n\n## 灵感\n\n- \n\n## 随记\n\n"

# 创建闪念笔记
obsidian-cli create "Fleeting/随想-$(date +%Y%m%d-%H%M)" --content "# 闪念 $(date +%H:%M)\n\n"
```
