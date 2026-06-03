# 大学人生纪录岛 - 版本规划

## 项目信息
- 名称：大学人生纪录岛 (Life Island)
- 仓库：Oren2026/LifeIsland ( CrazyOpenClaw-OpenCode/life-island branch )
- 创建日期：2026-06-03
- 版本：v1.0.0

---

## 版本变更日志 (CHANGELOG)

### v1.0.0 (2026-06-03)
- ✅ Phase 1: 岛屿首页 (index.html)
- ✅ Phase 2: 时间轴 (timeline.html)  
- ✅ Phase 3: 成就徽章墙 (badges.html)
- ✅ Phase 4: 技能树 (skills.html)

---

## 文件清单

| 版本 | 文件 | 说明 | 状态 |
|------|------|------|------|
| v1.0.0 | index.html | 岛屿首页/导航 | ✅ DONE |
| v1.0.0 | timeline.html | 大学四年时间轴 | ✅ DONE |
| v1.0.0 | badges.html | 成就徽章墙 | ✅ DONE |
| v1.0.0 | skills.html | 技能树 | ✅ DONE |
| v1.1.0 | capsules.html | 回忆胶囊 | 📋 PLANNED |
| v1.1.0 | messages.html | 留言板 | 📋 PLANNED |

---

## 下一步计划 (Next)

### 待完成 (v1.1.0)
- [ ] 回忆胶囊页面：有日期封存、可以开启
- [ ] 留言板页面：可以留言、保存localStorage

### 未来考虑
- [ ] 岛屿地图互动
- [ ] 游戏化积分系统
- [ ] 导出功能

---

## 工作流程

```
1. Oren 分析需求 → 写 prompt + 版本记录
              ↓
2. OpenCode 读取 prompt.md → 执行
              ↓
3. 完成 → 写入 .html + 更新 CHANGELOG.md
              ↓
4. Push to GitHub (life-island branch)
              ↓
5. Review → 确认没问题 → PR to main
```

---

## Prompt 规范

每一次给 OpenCode 的指令：
1. 先读取 CHANGELOG.md 了解当前进度
2. 明确版本号
3. 指定输出文件名
4. 规定任务完成后更新 CHANGELOG.md