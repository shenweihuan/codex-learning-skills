---
name: instant-memory-helper
description: Use this skill when the user is short on time and wants boring, abstract, dense, or exam-heavy material converted directly into memorable forms without learning memory theory first. Trigger on phrases such as 帮我快速记住, 没时间学记忆法, 考前速记, 把这些变好记, 枯燥知识记忆, 抽象概念记忆, 速背, 背不下来, or 用记忆法处理这段内容.
---

# Instant Memory Helper

This skill is for urgent memory transformation. The user does not need to learn memory theory. Convert their material into a compact memory package, then give a fast recall test and review plan.

## First Move

1. Extract the user's material and deadline.
2. If the material is missing, ask for it. If the deadline is missing, assume urgent but not same-hour.
3. Classify the material:
   - word list
   - definitions
   - ordered process
   - comparison
   - formula
   - essay/template
   - mixed exam notes
4. Produce the smallest useful memory package. Do not teach a long lesson.
5. Before finalizing, run the urgent quality gate: exact recall, image strength, exam fit, cognitive load, and closed loop. If cognitive load or exact recall is weak, simplify the package first.

## Output Contract

Always output:

```markdown
## 记忆包
[mnemonic transformation]

## 为什么这样好记
[one short reason, no theory lecture]

## 30秒自测
[active recall prompt]

## 易错点
[1-3 traps]

## 复习安排
[now / tonight / tomorrow / pre-exam]
```

## Transformation Rules

- For lists: use story chain or peg system.
- For ordered material: use memory palace or step symbols.
- For abstract definitions: use image association plus contrast.
- For confusable concepts: use contrast table and decision question.
- For formulas: use meaning labels plus one problem; do not rely on mnemonic alone.
- For English words: use sound/shape hook, vivid image, meaning, and one exam sentence.
- For long notes: chunk first, then transform only the high-value chunks.

Read `references/pattern-bank.md` for output patterns.
Read `references/content-routing.md` for material classification.
Read `references/review-mini.md` for urgent review schedules.
Read `references/evaluation-rubric.md` when judging whether a memory package is good enough.
Read `references/real-sample-tests.md` when running CET-4 vocabulary, writing-template, or abstract-knowledge test prompts.
Read `references/evaluation-results.md` when continuing optimization from the latest before/after dry-run results.
Read `references/source-index.md` only if the user asks what memory traditions this is based on.

## Quality Rules

- Speed beats elegance for urgent users.
- Every mnemonic must point back to the exact answer, not just a vague topic.
- Make images concrete and slightly strange, but keep them acceptable for study use.
- Do not over-process material that needs reasoning; mark it as "must understand first" and give a smaller memory cue.
- Preserve exam accuracy. If a vivid story distorts the definition, fix the story.
- For vocabulary, include spelling or usage recall when the exam may test production.
- For writing templates, memorize a flexible skeleton and substitutions, not a rigid paragraph.
- For abstract ideas, include one plain meaning and one application cue.

## Fallbacks

- If content is too long, ask the user to paste the most important page or choose top 10 items. If they cannot choose, extract likely high-frequency items and say that selection is approximate.
- If the subject is unfamiliar, keep the mnemonic structure generic and avoid making factual claims beyond the provided material.
- If the user has less than one hour, produce only high-yield cues and one recall drill.
