# 🦑 Arkham Case Files — AI 守秘人

AI 驱动的克苏鲁的呼唤（CoC 7th）多人跑团主持人。手机端 React Native 应用，AI 担任守秘人，玩家用手机加入房间，即开即玩。

## 这是什么

传统的 CoC 跑团需要一个真人守秘人（KP）——读规则书、准备模组、即兴叙事、执行检定。大多数想玩的人找不到 KP。

Arkham Case Files 用 AI 解决这个问题：玩家打开 App 进入房间，AI 自动主持游戏——推进剧情、执行 D100 检定、管理 SAN 值变化、分发私密线索。

## 技术栈

| 层 | 技术 |
|---|------|
| 前端 | React Native（TypeScript） |
| 后端 | Python FastAPI |
| AI | DeepSeek / Claude（待评估） |
| 规则引擎 | CoC 7th，硬编码 |

## 开发状态

> **MS1（第 1-2 周）**：战略决策 + 首尾可跑版本

- [x] 战略决策文档 v1.0 + 产品提案 v1.0 + 3 份窄提案
- [x] API 契约文档（反向分析前端生成）
- [x] 前端 10 屏交互原型（React 19 + Vite 8，Mock 模式可用）
- [x] 后端 FastAPI 骨架 + DeepSeek AI 叙事集成（LWC）
- [x] 前后端联调贯通（注册→房间→角色→大厅→AI 对话）
- [ ] MS1 路演准备

## 团队

6 人 · 1024 Techcamp 第 6 期 · 2026 年 7–8 月

## 许可

MIT
