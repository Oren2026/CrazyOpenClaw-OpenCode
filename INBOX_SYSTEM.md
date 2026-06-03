# 资讯处理系统 (Inbox System)

## 概述
这是「输入 → 分析 → 输出」的自动化流程，用来整理黑皮给我的资讯。

## 资料夹结构

```
/tmp/LifeIsland/inbox/
├── pending/       ← 等待处理的新内容
├── processed/   ← 已处理（可清除）
└── output/      ← 准备输出到岛屿的内容
```

## 工作流程

```
[黑皮给内容]
       ↓
[我读取 inbox/pending/]
       ↓
[分析资讯]
 │ 判断类型：
 │ ├─ 行事历事件 → calendar.html
 │ ├─ 技能/成就 → skills.html / badges.html
 │ ├─ 日志/心得 → CHANGELOG.md
 │ └─ 需要开发 → 给 OpenCode 执行
       ↓
[OpenCode 执行（如需要）]
       ↓
[输出到岛屿系统]
       ↓
[清空 inbox/processed/]
       ↓
[更新 CHANGELOG.md]
```

## OpenCode 合作原则

1. **每一次任务** → 先读取 prompt.md 了解需求
2. **执行后** → 更新 CHANGELOG.md 记录
3. **版本控管** → 通过 life-island 分支 push

## 使用时机

- 需要写代码/修改网页 → 交给 OpenCode
- 需要分析/判断/决策 → 我来处理
- 需要清空整理 → 处理完后清资料夹

## 最后更新
2026-06-03