---
title: "Week 1 Proof-of-Work Pack"
created: 2026-05-19
tags: [AI-Web3-School, Week1, Proof-of-Work, Hermes]
status: developing
---

# Week 1 Proof-of-Work Pack

> 提交时间：2026-05-19（截止：长期有效，建议本周内提交）
> 学号：4281

## 已完成的课程任务

### 前置准备（已提交）

| 任务 | 学分 | 已完成 |
|------|------|--------|
| 创建课程 GitHub repo | +10 | ✅ |
| 完成课程工具准备 | +10 | ✅ |
| 完成 Proof-of-Work 提交测试 | +5 | ✅ |
| 加入课程社群并完成自我介绍 | +10 | |

### AI 向任务

| 任务 | 学分 | 状态 | 产出 |
|------|------|------|------|
| 完成 Learning Agent Setup | +20 | ✅ | Hermes Agent 配置完成 |
| 整理 AI 基础概念卡片 | +10 | ✅ | [概念卡片 HTML](./experiments/ai-web3-concept-cards.html) |
| 完成 AI 可交互学习产物 | +30 | ✅ | [Week 1 Quiz](./experiments/week1-quiz.html) |

### 观看回放

| 课程 | 学分 | 状态 |
|------|------|------|
| 5.19 AI Agent 入门：Hermes 从 0 到 1 | +10 | ✅ |

## Learning Agent 配置说明

**工具**：Hermes Agent（WebUI 模式）
**模型**：DeepSeek V4 Pro
**Skills 加载**：花叔 Design、OCRs、数据科学等

### 学习工作流

1. Cron 每日 20:00 提醒 → 读取 WCB Learning 页面
2. 生成 daily/YYYY-MM-DD.md 到 GitHub repo
3. 实验产物放入 experiments/ 目录
4. 每日 commit + push

### 配置截图

> `profile.md`、`daily/2026-05-19.md`、`experiments/` 等均在 GitHub repo 中

## 本周交付物清单

| 交付物 | 链接 |
|--------|------|
| GitHub Repo | [ai-web3-school-cohort-0](https://github.com/1q2qq789/ai-web3-school-cohort-0) |
| Learning Agent 配置说明 | 本文件 |
| AI 基础概念卡片 | [experiments/ai-web3-concept-cards.html](https://github.com/1q2qq789/ai-web3-school-cohort-0/blob/main/experiments/ai-web3-concept-cards.html) |
| 可交互 Quiz | [experiments/week1-quiz.html](https://github.com/1q2qq789/ai-web3-school-cohort-0/blob/main/experiments/week1-quiz.html) |
| 每日学习记录 5.19 | [daily/2026-05-19.md](https://github.com/1q2qq789/ai-web3-school-cohort-0/blob/main/daily/2026-05-19.md) |

## 待完成（本周内）

- [ ] 测试网交易（+20）
- [ ] 部署最小合约（+30）
- [ ] AI × Web3 最小交叉流程图（+30）
- [ ] 行业关注清单（+20）
- [ ] 发布 X 学习总结（+20）

## 遇到的问题与人工修正

1. **GitHub Token 权限不足**：原 PAT 缺少 `public_repo` scope → 浏览器登录 GitHub 创建带 `public_repo` 的新 PAT
2. **Twitter 视频下载慢**：HLS 流 350MB 走代理速度不足 → 改用 600k low-bitrate 抽 3 分钟音频，但仍需 Whisper 模型下载大文件 → 最终以推文文本 + 演讲者资料推理总结

## 下一周计划

- 完成 Web3 基础任务（测试网 + 合约）
- 进入 Week 2 交叉方向（倾向 Dev Tooling / Agentic Commerce）
- 准备 Hackathon 项目 proposal
