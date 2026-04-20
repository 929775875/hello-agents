# Chapter 15: Building Cyber Town｜笔记

## 核心主题
In this chapter, we will explore a brand new direction: **combining agent technology with game engines to build an AI town full of vitality**.

## 章节结构
- Project Overview and Architecture Design
- NPC Agent System
- Affection System Design
- Back-End Service Implementation
- Godot Game Scene Construction
- Front-End and Back-End Communication Implementation
- Summary and Outlook

## 各节速记
### Project Overview and Architecture Design
- NPCs in traditional games can usually only say fixed lines or have limited interactions through preset dialogue trees...

### NPC Agent System
- In Cyber Town, each NPC is an independent agent. We use SimpleAgent from the HelloAgents framework to implement NPC i...

### Affection System Design
- In Cyber Town, NPC attitudes towards players change with interactions. We designed a five-level affection system, fro...

### Back-End Service Implementation
- The back-end of Cyber Town is built using the FastAPI framework, responsible for handling requests from the Godot fro...

### Godot Game Scene Construction
- Why Choose Godot as the Game Engine?

### Front-End and Back-End Communication Implementation
- The Godot front-end needs to communicate with the FastAPI back-end via HTTP. We create an API client script api_clien...

### Summary and Outlook
- In this chapter, we completed a full AI town project - Cyber Town. This project combines the HelloAgents framework wi...

## 关键词
Project、Overview、and、Architecture、Design、NPC、Agent、System、Affection、Back

## 复习清单
- 我能解释本章核心概念与适用场景。
- 我能复述关键流程，并指出输入、输出与评估指标。
- 我能独立复现实验或代码示例，并说明常见失败原因。
- 我能将本章方法迁移到自己的项目需求中。
