# Real Sample Test Matrix

These tests are grounded in WeRead source discovery plus small self-contained CET-4 examples. Do not copy book passages into outputs.

## WeRead Source Signals

- `22787990` 四级英语新大纲词汇表, 新东方考试研究中心. Usable signal: CET-4 vocabulary list structure; no popular highlights available in probe.
- `3300100928` (24)四级写作与翻译考前预测20篇, 王江涛. Usable signal: chapters emphasize recitation, dictation, imitation, and avoiding unnecessarily difficult wording.
- `3300034509` 超级记忆, 东尼·博赞. Usable signal: association, linking, and vivid imagery tradition.
- `22515168` 记忆魔法师：学习考试实用记忆宝典（全新修订版）, 袁文魁. Usable signal: exam-oriented memory practice and practical memory training.

## Six Test Prompts

### CET-4 Vocabulary 1

Prompt: `我想学习联想记忆，用四级词 abandon, acquire, domestic, efficient, evidence, transform 练习。`

Expected:
- Teach image association briefly.
- Create hooks for 2-3 words, then make the user complete the rest.
- Include spelling recall, meaning recall, and one example-sentence blank.
- Score later attempts with the rubric.

### CET-4 Vocabulary 2

Prompt: `我总把 affect/effect, economic/economical, adapt/adopt 记混，帮我用记忆法训练。`

Expected:
- Use contrast table plus image cue.
- Include decision rules for choosing the right word.
- Include a 30-second mixed quiz.

### CET-4 Writing 1

Prompt: `教我用记忆宫殿背四级作文结构：现象引入、原因一、原因二、例子、结论。`

Expected:
- Use 5-location palace.
- Require the user to paraphrase, not recite rigidly.
- Include a blank outline recall test.

### CET-4 Writing 2

Prompt: `我想记住一个四级观点类作文模板，但怕死背，帮我练背诵、默写、仿写。`

Expected:
- Use three-stage drill: recite skeleton, write from memory, imitate with a new topic.
- Include self-check criteria for template flexibility.

### Abstract Knowledge 1

Prompt: `我想真正记住遗忘曲线、主动回忆、间隔复习、组块化之间的关系。`

Expected:
- Use chunking plus story or map.
- Separate understanding from recall cue.
- Include "explain without looking" test.

### Abstract Knowledge 2

Prompt: `我学了地点法但总失败，帮我诊断为什么路线和图像第二天就忘。`

Expected:
- Diagnose cue, image, route stability, overload, and review timing.
- Give repair actions and a retest schedule.

## Dry-Run Score Summary

| Skill | Baseline | After Required Changes | Main Gain |
|---|---:|---:|---|
| memory-method-coach | 18-21/25 | 22-24/25 | Stronger self-test, trap handling, feedback scoring |

