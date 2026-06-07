# Real Sample Test Matrix

These tests are grounded in WeRead source discovery plus small self-contained CET-4 examples. Do not copy book passages into outputs.

## WeRead Source Signals

- `22787990` 四级英语新大纲词汇表: use as CET-4 vocabulary source direction.
- `3300100928` (24)四级写作与翻译考前预测20篇: use as writing-and-translation exam source direction, especially recite/write/imitate practice.
- `3300034509` 超级记忆: use as association and linking source direction.
- `22515168` 记忆魔法师：学习考试实用记忆宝典（全新修订版）: use as exam-memory source direction.

## Six Test Prompts

### CET-4 Vocabulary 1

Prompt: `明天四级，帮我快速记住 abandon, acquire, domestic, efficient, evidence, transform。`

Expected:
- Compact word table with hook, meaning, spelling cue, and one example-sentence blank.
- 30-second cover-and-recall test.

### CET-4 Vocabulary 2

Prompt: `我没时间学方法，直接帮我区分 affect/effect, economic/economical, adapt/adopt。`

Expected:
- Decision rules and contrast hooks.
- Mini quiz with mixed blanks.

### CET-4 Writing 1

Prompt: `把观点类四级作文结构变成好记的考前记忆包：现象、原因、例子、建议、结论。`

Expected:
- Five-location palace or five-symbol skeleton.
- No long theory.
- One 30-second oral recall test.

### CET-4 Writing 2

Prompt: `我今晚只想背一个作文万能框架，明天能套 online learning 和 environmental protection。`

Expected:
- Flexible frame, two topic substitutions, warning against rigid copied sentences.

### Abstract Knowledge 1

Prompt: `快速帮我记住主动回忆、间隔复习、组块化、联想、迁移这五个概念。`

Expected:
- One short story or route.
- Each concept has a one-line meaning.
- 30-second self-test.

### Abstract Knowledge 2

Prompt: `把“遗忘不是失败，而是强化提取的时机”这句话变好记。`

Expected:
- Concrete image plus exact sentence recall.
- Trap: do not reread only; must recall first.

## Dry-Run Score Summary

| Skill | Baseline | After Required Changes | Main Gain |
|---|---:|---:|---|
| instant-memory-helper | 17-20/25 | 22-24/25 | Lower load, stronger tests, better exact recall |

