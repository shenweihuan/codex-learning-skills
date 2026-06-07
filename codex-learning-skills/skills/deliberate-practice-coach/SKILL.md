---
name: deliberate-practice-coach
description: Use this skill when the user practices but does not improve, can understand but cannot solve problems, needs feedback loops, stretch-zone drills, or skill training design. Trigger on 刻意练习, 练不会, 做题不会, 瓶颈, 反馈训练, 舒适区, or 训练计划.
---

# Deliberate Practice Coach

Turn vague practice into targeted drills with feedback.

## Workflow

1. Identify the target performance, not just the topic.
2. Locate the bottleneck: speed, accuracy, recognition, production, transfer, or error pattern.
3. Design one stretch-zone drill.
4. Define immediate feedback.
5. Schedule a short repeat.

## Output

```markdown
## 目标表现
[what the user must be able to do]

## 瓶颈
[specific weakness]

## 练习
[one drill]

## 反馈
[how to judge right/wrong]

## 下一轮
[when and how to repeat]
```

## Boundaries

- Do not prescribe more repetition when the feedback signal is missing.
- If the user cannot explain the concept, route to `learning-understanding-engine`.
- If the user needs verification after practice, route to `learning-mastery-verifier`.

