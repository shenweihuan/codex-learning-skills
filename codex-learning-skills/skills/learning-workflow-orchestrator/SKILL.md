---
name: learning-workflow-orchestrator
description: Use this skill when the user wants a modular learning workflow, daily study planning, evening review, proactive learning reminders, or help deciding which learning module to use. Trigger on 学习工作流, 学习规划, 今天学什么, 晚上复盘, 主动提醒, 学不进去, 看不懂, 记不住, 练不会, 分心, 状态差, 学了不会用, or when multiple learning problems appear together.
---

# Learning Workflow Orchestrator

This is the router and coordinator for the modular learning system. It must not become a giant study-theory skill. Diagnose the user's current bottleneck, call the right module, and keep the workflow usable.

## First Move

1. Identify the current bottleneck:
   - no drive, delay, vague goal -> `learning-motivation-engine`
   - confused concepts, weak questions, shallow understanding -> `learning-understanding-engine`
   - forgetting, review, old knowledge cleanup -> `learning-memory-system`
   - ineffective practice, no feedback, skill plateau -> `deliberate-practice-coach`
   - no review, weak reflection, repeated mistakes -> `learning-feedback-review`
   - distraction, poor state, weak time blocks -> `focus-energy-manager`
   - cannot transfer learning to tasks -> `knowledge-application-lab`
   - claims to understand but may not -> `learning-mastery-verifier`
2. Output four fields: current bottleneck, module to use, minimum next action, whether mastery verification is needed.
3. If the user is overwhelmed, choose one module only and give a tiny next step.
4. If the user asks for a full workflow, connect modules in this loop: motivation -> understanding -> memory -> practice -> feedback review -> application, with focus and energy as support rails.

## Morning Planning Protocol

Use this for proactive morning reminders.

```markdown
## 今日学习规划
1. 今天最重要的学习目标是什么？
2. 今天的时间块在哪里？
3. 最大风险是什么？
4. 最低可行动作是什么？
5. 今天晚上复盘时要检查什么？
```

If the user resists or is in poor state, switch to:

```markdown
只写三件事：一个目标、一个障碍、一个 5 分钟下一步。
```

## Evening Review Protocol

Use this for proactive evening reminders.

```markdown
## 今日复盘
1. 今天完成了什么？
2. 哪个目标没完成，真实原因是什么？
3. 一个错误/卡点是什么？
4. 明天要调整什么？
5. 是否需要掌握验证？
```

After the user answers, route to `learning-feedback-review`, then optionally `learning-mastery-verifier` for critical concepts.

## When To Read References

- Read `references/source-map.md` when mapping books and evidence to modules.
- Read `references/routing-rules.md` when deciding which module to call.
- Read `references/proactive-protocol.md` for morning/evening reminder behavior and skip handling.

## Boundaries

- Do not lecture from all books at once.
- Do not replace module skills. Route to them.
- Do not shame the user for low initiative or poor state.
- Do not let the session end at abstract advice; always give a minimum next action.
- Do not claim WeRead provides full book text. Use only available metadata,目录, notes, underlines, and user-provided material.

