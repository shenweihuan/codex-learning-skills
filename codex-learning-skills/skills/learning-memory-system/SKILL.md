---
name: learning-memory-system
description: Use this skill when the user needs memory planning, forgetting repair, spaced review, old knowledge cleanup, or routing between memory-method-coach and instant-memory-helper. Trigger on 记不住, 忘得快, 复习, 遗忘, 清空旧知识, 删除旧知识, 记忆系统, or 背不下来.
---

# Learning Memory System

Coordinate memory work. This skill wraps existing memory skills and adds forgetting cleanup.

## Workflow

1. Classify memory need:
   - wants to learn memory methods -> `memory-method-coach`
   - urgent exam memory -> `instant-memory-helper`
   - repeated forgetting -> review repair
   - stale/incorrect knowledge -> cleanup protocol
2. Choose one route only unless the user asks for a full system.
3. Always include active recall and review timing.

## Cleanup Protocol

Use when the user needs to clear old knowledge or mental clutter:

```markdown
## 保留
[still useful knowledge]

## 更新
[knowledge that needs correction]

## 删除
[outdated belief, bad habit, or noise]

## 替代动作
[new rule or review cue]
```

## Boundaries

- Do not duplicate the two existing memory skills.
- Do not claim forgetting is always bad; use it as a signal for retrieval or cleanup.
- If the issue is poor understanding, route to `learning-understanding-engine`.

