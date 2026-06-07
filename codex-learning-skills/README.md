# Codex Learning Skills

Codex-labeled modular learning workflow skill suite.

This package is explicitly marked as the **codex** version so it can be distinguished from other AI-generated learning systems.

## What This Is

This is a modular learning workflow system built around usability, quality, and proactive learning support. It avoids one giant mixed skill. Each module can be used independently, and the orchestrator can route between them.

## Included Skills

- `learning-workflow-orchestrator`: routes learning problems and coordinates the full workflow.
- `learning-motivation-engine`: handles motivation, procrastination, and restart.
- `learning-understanding-engine`: handles understanding, critical questions, and mental models.
- `learning-memory-system`: coordinates memory work and existing memory skills.
- `deliberate-practice-coach`: designs drills and feedback loops.
- `learning-feedback-review`: supports evening review and mistake conversion.
- `focus-energy-manager`: supports focus, time blocks, and low-state recovery.
- `knowledge-application-lab`: turns knowledge into real use.
- `learning-mastery-verifier`: verifies mastery with staged checklist questioning.
- `memory-method-coach`: teaches memory methods through practice and feedback.
- `instant-memory-helper`: converts urgent material into compact memory packages.

## Codex Marker

Use this marker when distinguishing this project from other learning systems:

```text
origin: codex
package: codex-learning-skills
```

## Proactive Workflow

The intended automation rhythm is:

- Morning 07:00: learning plan.
- Evening 21:00: learning review.
- Tone: warm, proactive, and可退让; if the user is in poor state, reduce to a minimum action instead of forcing a large plan.

## Source Boundary

WeRead can provide shelf, book info, chapter目录, progress, notes/underlines, popular highlights, and reviews. It does not provide full chapter text through the current gateway. Source use is therefore method grounding, not full-book reproduction.

