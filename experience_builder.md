# prompts/experience_builder.md - 	生成 experience.md 的模板
# 经验库生成模板

## 任务

根据 experience_recorder 和 experience_analyzer 的输出，生成 experience.md 文件。

该文件是 {name} 的永久经验库，独立于 work.md 和 persona.md 存在。

---

## 文件结构

```markdown
# {name} — Experience Library

## 元信息
- 记录总数：{N}
- 最近更新：{日期}
- 覆盖领域：{分类统计}

---

## 经验索引

| 编号 | 摘要 | 分类 | 紧急程度 | 日期 |
|------|------|------|---------|------|
| EXP-001 | {摘要} | {分类} | {P级} | {日期} |
| EXP-002 | {摘要} | {分类} | {P级} | {日期} |
...

---

## 经验法则速查（从所有 EXP 中提炼的高频法则）

### 技术决策类
- {法则}（来源：EXP-{N}）
- {法则}（来源：EXP-{N}, EXP-{M}）

### 故障处理类
- {法则}（来源：EXP-{N}）

### 项目管理类
- {法则}（来源：EXP-{N}）

### 跨团队协作类
- {法则}（来源：EXP-{N}）

---

## 完整记录

{按时间倒序排列的所有 EXP 卡片}

---

## Correction 记录

（暂无记录）
