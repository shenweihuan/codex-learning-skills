# Codex Learning Skills

**Codex-labeled lightweight proactive learning workflow suite.**

This repository is the **codex** version of a modular learning skill system. It is not meant to replace the heavier `learning-system` repositories. Its job is simpler and more practical: help a Codex-style agent actively guide daily learning with planning, review, focus recovery, memory support, practice loops, and mastery checks.

## Start Here

The skill package lives in:

```text
codex-learning-skills/
```

Use the orchestrator first:

```text
learning-workflow-orchestrator
```

It routes the user to the right module when they say things like:

- "I do not want to study today."
- "I understand it but cannot solve problems."
- "I keep forgetting."
- "Remind me to plan in the morning."
- "Help me review tonight."

## Why This Exists

The other learning-system repositories are broad source-heavy systems. This one is the Codex-specific execution layer:

- lighter
- easier to call module by module
- marked clearly as `codex`
- built around morning planning and evening review
- designed to keep working when the user is tired, avoidant, or low-energy

## Relationship To Other Repositories

| Repository | Role |
|---|---|
| `learning-system` | comprehensive learning workflow, source-heavy, M00-M09 |
| `learning-system-v2` | enhancement layer for thinking models, habits, knowledge management, deep work |
| `codex-learning-skills` | Codex-labeled lightweight proactive workflow suite |

## Included Modules

- `learning-workflow-orchestrator`
- `learning-motivation-engine`
- `learning-understanding-engine`
- `learning-memory-system`
- `deliberate-practice-coach`
- `learning-feedback-review`
- `focus-energy-manager`
- `knowledge-application-lab`
- `learning-mastery-verifier`
- `memory-method-coach`
- `instant-memory-helper`

## Codex Marker

```text
origin: codex
package: codex-learning-skills
```

Every included skill copy also contains `CODEX_ORIGIN.md` so this suite can be distinguished from other AI-generated learning systems.

