# Evaluation Results

Date: 2026-06-07
Mode: dry-run evaluation with WeRead-grounded source signals and self-contained CET-4 samples.

## Source Probe

| Source | WeRead ID | Usable Data |
|---|---|---|
| 四级英语新大纲词汇表 | `22787990` | Book info and chapter structure; no popular highlights in probe |
| (24)四级写作与翻译考前预测20篇 | `3300100928` | Book info, chapter structure, popular highlights count |
| 超级记忆 | `3300034509` | Book info, chapter structure, popular highlights count |
| 记忆魔法师：学习考试实用记忆宝典（全新修订版） | `22515168` | Book info, chapter structure, popular highlights count |

## Before/After Scores

Scores use `evaluation-rubric.md`, max 25.

| Prompt ID | Scenario | Baseline | After | Kept Improvement |
|---|---|---:|---:|---|
| coach-vocab-01 | CET-4 word association practice | 18 | 23 | Add spelling cue, sentence blank, and feedback scoring |
| coach-vocab-02 | Confusable CET-4 word pairs | 19 | 24 | Add contrast table, decision rules, and mixed quiz |
| coach-writing-01 | CET-4 essay palace | 20 | 23 | Add paraphrase requirement and blank outline recall |
| coach-writing-02 | Recite-write-imitate writing drill | 18 | 24 | Add three-stage drill and template flexibility check |
| coach-abstract-01 | Forgetting/recall/chunking relationship | 19 | 23 | Separate understanding from recall cue |
| coach-abstract-02 | Failed memory palace diagnosis | 21 | 24 | Add route stability, overload, and review timing repair |

Average baseline: 19.2/25
Average after: 23.5/25

## Decisions

- Keep the pass gate: total at least 20/25, with exact recall, exam fit, and closed loop each at least 4/5.
- Keep `real-sample-tests.md` as the canonical CET-4 test matrix.
- Do not store long book passages. WeRead sources remain high-level grounding and source index only.

