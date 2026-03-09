---
title: "EduAtlas 全览地图"
stage: "all"
subject: "general"
module: "全览地图"
tags: ["导航", "全览", "知识体系"]
importance: "key"
difficulty: "basic"
priority: "P0"
last_updated: "2026-03-06"
---

# EduAtlas 全览地图

> 一张图看清从幼小衔接到小学毕业的完整知识体系。点击任意阶段进入详情。

## 1. 全景知识图谱

```mermaid
graph TD
    classDef default fill:#5BA4B5,stroke:#999,color:#2D2D2D
    classDef key fill:#F4A6A0,stroke:#999,color:#2D2D2D
    classDef tip fill:#F5C28E,stroke:#999,color:#2D2D2D
    classDef adv fill:#B8A9D4,stroke:#999,color:#2D2D2D
    classDef done fill:#A8D8B9,stroke:#999,color:#2D2D2D

    K0[K0 幼小衔接]:::done ==> K1U[K1 上册]:::default
    K1U ==> K1D[K1 下册]:::default
    K1D ==> K2U[K2 上册]:::default
    K2U ==> K2D[K2 下册]:::default
    K2D ==> K3U[K3 上册]:::default
    K3U ==> K3D[K3 下册]:::default
    K3D ==> K4U[K4 上册]:::default
    K4U ==> K4D[K4 下册]:::default
    K4D ==> K5U[K5 上册]:::default
    K5U ==> K5D[K5 下册]:::default
    K5D ==> K6U[K6 上册]:::default
    K6U ==> K6D[K6 下册]:::default

    K0 -.- H0[习惯养成]:::key
    K0 -.- C0[语文启蒙]:::tip
    K0 -.- M0[数学启蒙]:::tip
    K0 -.- P0[实用准备]:::adv
```

> 图例：绿色 = 已完成 | 蓝色 = 待建设 | 红色 = 习惯 | 橙色 = 学科 | 紫色 = 实用

## 2. 阶段总览

| 阶段 | 名称 | 核心目标 | 内容数 | 状态 | 入口 |
|------|------|----------|--------|------|------|
| K0 | 幼小衔接 | 习惯建立 + 基础启蒙 + 入学准备 | 13 篇 | 已完成 | [进入](K0-preschool/README.md) |
| K1 上 | 一年级上学期 | — | — | 待建设 | — |
| K1 下 | 一年级下学期 | — | — | 待建设 | — |
| K2 上 | 二年级上学期 | — | — | 待建设 | — |
| K2 下 | 二年级下学期 | — | — | 待建设 | — |
| K3 上 | 三年级上学期 | — | — | 待建设 | — |
| K3 下 | 三年级下学期 | — | — | 待建设 | — |
| K4 上 | 四年级上学期 | — | — | 待建设 | — |
| K4 下 | 四年级下学期 | — | — | 待建设 | — |
| K5 上 | 五年级上学期 | — | — | 待建设 | — |
| K5 下 | 五年级下学期 | — | — | 待建设 | — |
| K6 上 | 六年级上学期 | — | — | 待建设 | — |
| K6 下 | 六年级下学期 | — | — | 待建设 | — |

## 3. 多视角索引

除了按阶段浏览，你还可以通过以下视角快速找到需要的内容：

| 视角 | 适合场景 | 链接 |
|------|----------|------|
| 按学科 | "我想看数学/语文相关的所有内容" | [按学科索引](indexes/by-subject.md) |
| 重难点速查 | "时间有限，只看重点" | [重难点速查](indexes/key-points.md) |
| 易错点清单 | "孩子老是错在哪里" | [易错点清单](indexes/common-mistakes.md) |

## 4. 如何使用本知识库

1. **首次访问**：先看本页全景图，了解整体结构
2. **确定阶段**：点击你孩子所在阶段的入口，进入阶段详情
3. **按需深入**：在阶段页面中，按推荐顺序阅读，或使用索引跳转到感兴趣的内容
4. **重点标记**：标注为"重点"或"难点"的内容优先阅读

---

*最后更新：2026-03-06*
