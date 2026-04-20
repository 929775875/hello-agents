# Chapter 9 Context Engineering｜笔记

## 核心主题
In previous chapters, we have introduced memory systems and RAG for agents. However, to enable agents to stably "think" and "act" in real complex scenarios, memory and retrieval alone are not enough—we need an engineering methodology to continuously and systematically construct appropriate "context" for the model. This is the theme of this chapter: Context Engineering. It focuses on "how to assemble and optimize input context in a reusable, measurable, and evolvable way before each model call", thereby improving correctness, robustness, and efficiency<sup>[1][2]</sup>.

## 章节结构
- What is Context Engineering
- Why Context Engineering is Important
- Practice in Hello-Agents: ContextBuilder
- NoteTool: Structured Notes
- Completion Status
- Test Coverage
- Next Steps
- Next Steps
- TerminalTool: Instant File System Access
- Long-Horizon Agent in Practice: Codebase Maintenance Assistant
- Task Checklist
- Schedule
- Risks
- Chapter Summary

## 各节速记
### What is Context Engineering
- After years of Prompt Engineering becoming the focus of applied AI, a new term has come to the forefront: Context Eng...

### Why Context Engineering is Important
- Although models are getting faster and can handle larger data scales, we observe that: like humans, LLMs will "wander...

### Practice in Hello-Agents: ContextBuilder
- This section will detail the context engineering practice in the HelloAgents framework. We will gradually demonstrate...

### NoteTool: Structured Notes
- NoteTool is a structured external memory component provided for "long-horizon tasks". It uses Markdown files as carri...

### Completion Status
- Completed refactoring of data model layer, main changes include:

### Test Coverage
- - Unit test coverage: 85%

### Next Steps
- 1. Refactor business logic layer

### Next Steps
- Refactor business logic layer""",

### TerminalTool: Instant File System Access
- In previous chapters, we introduced MemoryTool and RAGTool, which provide conversational memory and knowledge retriev...

### Long-Horizon Agent in Practice: Codebase Maintenance Assistant
- Now, let's integrate ContextBuilder, NoteTool, and TerminalTool to build a complete long-horizon agent—Codebase Maint...

### Task Checklist
- - [ ] Add unique constraint to User.email

### Schedule
- - Monday: Design migration scripts

## 关键词
What、is、Context、Engineering、Why、Important、Practice、in、Hello、Agents

## 复习清单
- 我能解释本章核心概念与适用场景。
- 我能复述关键流程，并指出输入、输出与评估指标。
- 我能独立复现实验或代码示例，并说明常见失败原因。
- 我能将本章方法迁移到自己的项目需求中。
