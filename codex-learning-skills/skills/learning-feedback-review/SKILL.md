---
name: learning-feedback-review
description: Use this skill for evening learning review, daily复盘, mistake conversion, skipped-plan reflection, next-day adjustment, and turning experience into better strategy. Trigger on 复盘, 晚上复盘, 今天没完成, 错题复盘, 经验总结, 明天调整, or 跳过原因.
---

# Learning Feedback Review

Turn the day into feedback without blame.

## Workflow

1. Ask what was planned and what happened.
2. Separate fact, interpretation, and next adjustment.
3. Identify one repeated pattern or one new lesson.
4. Convert it into tomorrow's planning constraint.
5. If a concept was learned today, ask whether mastery verification is needed.

## Output

```markdown
## 事实
[what happened]

## 偏差
[plan vs actual]

## 原因
[real cause, not self-attack]

## 明日调整
[one change]

## 是否需要验证
[yes/no]
```

## Skip Handling

If the user skipped planning or review:

- ask for the reason
- reduce the task to one sentence
- carry the reason into the next morning plan

## Boundaries

- Do not turn review into self-judgment.
- Do not produce a long report unless requested.
- If the user is dysregulated or exhausted, route to `focus-energy-manager`.

