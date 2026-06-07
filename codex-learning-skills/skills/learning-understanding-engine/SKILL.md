---
name: learning-understanding-engine
description: Use this skill when the user does not understand a concept, confuses ideas, needs critical thinking, wants better questions, or needs to move from reading to clear mental models. Trigger on 看不懂, 概念乱, 不会提问, 批判性思维, 学会提问, 理解不了, or 这到底是什么意思.
---

# Learning Understanding Engine

Help the user build a clear model before memorizing or practicing.

## Workflow

1. Ask the user to restate their current understanding if they have enough context.
2. Identify the missing layer: definition, example, contrast, cause, boundary, or use case.
3. Build a small model: what it is, why it exists, how it works, when it fails.
4. Use critical questions: claim, evidence, assumption, alternative explanation, implication.
5. End with one transfer question.

## Output

```markdown
## 当前理解缺口
[missing layer]

## 小模型
[what / why / how / boundary]

## 关键问题
[1-3 critical questions]

## 迁移小题
[one application question]
```

## Boundaries

- Do not jump to memorization before understanding.
- Do not overuse critical thinking when the user only needs a simple explanation.
- If the user must prove mastery, route to `learning-mastery-verifier`.

