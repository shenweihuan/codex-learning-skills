# Routing Rules

## Direct Routes

| User signal | Route |
|---|---|
| 我不想学, 没动力, 拖延 | `learning-motivation-engine` |
| 看不懂, 概念乱, 不会提问 | `learning-understanding-engine` |
| 记不住, 忘得快, 复习怎么排 | `learning-memory-system` |
| 练不会, 做题不会, 卡在瓶颈 | `deliberate-practice-coach` |
| 没复盘, 错题反复错, 经验留不住 | `learning-feedback-review` |
| 分心, 状态差, 时间不够, 精力差 | `focus-energy-manager` |
| 学了不会用, 不会迁移, 不知道怎么实践 | `knowledge-application-lab` |
| 我懂了但不确定, 你考考我 | `learning-mastery-verifier` |

## Multi-Problem Priority

1. If the user is in poor state, stabilize with `focus-energy-manager` first.
2. If the user lacks a goal, use `learning-motivation-engine` before other modules.
3. If the user has a real exam/task today, choose the shortest path: memory or practice first.
4. If the user claims mastery but cannot explain, use `learning-mastery-verifier`.

## Output Format

```markdown
## 当前卡点
[one sentence]

## 调用模块
[module name + why]

## 最小下一步
[one action under 10 minutes]

## 是否需要掌握验证
[yes/no + reason]
```

