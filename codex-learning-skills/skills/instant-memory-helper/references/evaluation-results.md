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
| instant-vocab-01 | Urgent CET-4 word pack | 17 | 23 | Add spelling/use check and 30-second recall |
| instant-vocab-02 | Confusable word quick distinction | 18 | 24 | Add decision rules and mixed blank quiz |
| instant-writing-01 | CET-4 structure memory package | 19 | 23 | Add five-symbol skeleton and oral recall |
| instant-writing-02 | One-night flexible writing frame | 18 | 23 | Add topic substitutions and anti-dead-memorization warning |
| instant-abstract-01 | Five learning concepts | 20 | 24 | Add one-line meanings and one short route/story |
| instant-abstract-02 | Exact sentence memory | 18 | 23 | Add concrete image, exact sentence recall, and rereading trap |

Average baseline: 18.3/25
Average after: 23.3/25

## Decisions

- Keep the urgent pass gate: total at least 20/25, with cognitive load, exact recall, and closed loop each at least 4/5.
- Prefer simplification over more theory when an urgent output fails.
- Do not store long book passages. WeRead sources remain high-level grounding and source index only.

