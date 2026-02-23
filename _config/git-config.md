# Git 配置备忘录

> 🔐 本文档记录 Obsidian Vault 的 GitHub 同步配置信息
> 📅 创建时间：2026-02-23
> ⚠️ **重要**：敏感信息已加密保存在 Kimi 记忆中

---

## 📦 仓库信息

- **仓库地址**：`https://github.com/abbozhang/kimi-obsidian-vault.git`
- **用户名**：`abbozhang`
- **仓库类型**：私有仓库
- **本地路径**：`/data/workspace/obsidian-vault`

---

## 🔑 认证信息

### Personal Access Token (PAT)

```
Token 格式：ghp_****************************
```

> 🔒 **完整 Token 已安全保存在 Kimi 的长期记忆中**  
> 你可以随时对 Kimi 说：
> - "显示完整的 GitHub Token"
> - "用我的 token 推送代码"
> - "配置 Git 认证"

**Token 详情：**
- 📝 **Token 名称**：Kimi Claw Sync
- 📅 **创建时间**：2026-02-23
- ⏰ **到期时间**：2026-05-24
- 🔐 **权限范围**：`repo`（完整控制私有仓库）
- ✅ **状态**：Active

### 到期提醒

- ⚠️ Token 将在 **2026年5月24日** 到期
- 📅 建议在 2026年5月中旬对 Kimi 说："重新生成 GitHub Token"

---

## 🛠️ Git 操作命令

### 让 Kimi 自动处理（推荐）✨

直接对 Kimi 说以下任何一句：

| 你想做什么 | 对 Kimi 说 |
|-----------|-----------|
| 推送更改到 GitHub | `"推送到 GitHub"` 或 `"同步笔记到远程"` |
| 从 GitHub 拉取更新 | `"拉取最新的笔记"` 或 `"同步远程更新"` |
| 查看当前状态 | `"检查 Git 状态"` 或 `"有什么改动？"` |
| 查看提交历史 | `"显示提交记录"` 或 `"最近的更新"` |
| 配置 Git 认证 | `"配置 Git Token"` 或 `"重新设置认证"` |

### 手动操作命令（高级用户）

```bash
# 配置远程仓库
# 注意：需要替换 [YOUR_TOKEN] 为实际 Token
git remote set-url origin https://abbozhang:[YOUR_TOKEN]@github.com/abbozhang/kimi-obsidian-vault.git

# 推送到远程仓库
git push origin main

# 从远程仓库拉取
git pull origin main

# 查看当前状态
git status

# 查看提交历史
git log --oneline -10
```

---

## 📁 Vault 文件结构

当前 vault 采用以下文件夹结构（2026-02-23 重构后）：

```
obsidian-vault/
├── Daily/          # 📅 每日日记 (格式: YYYY-MM-DD.md)
├── Inbox/          # 📥 临时收集箱，未整理的想法和笔记
├── Knowledge/      # 📚 永久知识库，已整理的专业知识
├── MOC/            # 🗺️ Map of Content，内容地图索引
├── _config/        # ⚙️ 系统配置文档（本文件所在位置）
├── skills/         # 🤖 自动化脚本和工具
└── README.md       # 📖 Vault 说明文档
```

### 重构说明

- ✅ 已合并重复的 `KimiVault/Daily/`、`KimiVault/Inbox/`、`KimiVault/MOC/` 到根目录
- ✅ 已重命名 `memory/` 为 `_config/`
- ✅ 所有 28 个 .md 文件完整保留
- 💾 备份分支：`backup-20260223-200002`

---

## 🔒 安全原则

1. ⚠️ **绝对不能丢失任何 .md 文件**
2. 🛡️ Token 不要明文保存在文件中（已由 Kimi 记忆管理）
3. 💾 重要操作前先创建备份分支
4. ⏰ Token 到期前及时更新
5. 🔐 本仓库已设置为私有，请勿公开

---

## 💾 备份与恢复

### 当前备份

- **备份分支**：`backup-20260223-200002`
- **备份时间**：2026-02-23 20:00
- **备份内容**：重构前的完整状态

### 恢复备份

如果需要回滚到重构前的状态：

```bash
git checkout backup-20260223-200002
```

或者对 Kimi 说：`"恢复到备份分支"`

---

## 🆘 故障排查

### ❌ Token 认证失败

**症状**：`git push` 时提示 "Invalid username or token"

**解决方法**：
1. 对 Kimi 说："检查 Token 是否有效"
2. 或对 Kimi 说："重新配置 Git Token"
3. 如果 Token 已过期，对 Kimi 说："生成新的 GitHub Token"

### ❌ 推送被拒绝

**症状**：`git push` 提示 "rejected"

**解决方法**：
1. 对 Kimi 说："先拉取远程更新"
2. 如果有冲突，Kimi 会帮你解决
3. 然后再推送

### ❌ 文件冲突

**症状**：拉取时提示 "CONFLICT"

**解决方法**：
1. 对 Kimi 说："帮我解决 Git 冲突"
2. Kimi 会分析冲突并提供建议
3. 确认后自动合并

---

## 📝 更新日志

| 日期 | 操作 | 说明 |
|------|------|------|
| 2026-02-23 | 🎯 初始化配置 | 创建 Git 配置备忘录 |
| 2026-02-23 | 🔑 Token 设置 | 生成 PAT，有效期至 2026-05-24 |
| 2026-02-23 | 🎨 结构重构 | 合并重复文件夹，规范化目录 |

---

## 🔗 相关链接

- 🏠 [GitHub 仓库](https://github.com/abbozhang/kimi-obsidian-vault)
- 🔑 [GitHub Token 管理](https://github.com/settings/tokens)
- 📚 [Git 官方文档](https://git-scm.com/doc)
- 💡 [Obsidian 官网](https://obsidian.md)

---

## 💡 使用建议

### 日常工作流

1. **早上打开 Obsidian 时**：
   - 对 Kimi 说："同步最新的笔记"
   
2. **写完笔记后**：
   - 对 Kimi 说："推送到 GitHub"
   
3. **定期检查**：
   - 对 Kimi 说："检查 vault 状态"

### 在不同设备间同步

- **在 MacBook 上**：通过 Obsidian 看到最新笔记
- **在 AnyDev 上**：通过 Kimi 管理和整理笔记
- **无缝协作**：两边通过 GitHub 自动同步 ✨

---

*📌 提示：Kimi 已记住所有配置，你只需要用自然语言告诉 TA 你想做什么！*
