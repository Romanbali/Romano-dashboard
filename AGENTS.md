# Agent guidance

For any task that creates, changes, or reviews UI motion or animation, consult the relevant skill in `.agents/skills/` before editing:

- Build or change an animation: `.agents/skills/animate/SKILL.md` and its `RECIPES.md`.
- Audit existing animation across the project: `.agents/skills/improve-animations/SKILL.md`.
- Review an animation implementation or diff: `.agents/skills/review-animations/SKILL.md` and `STANDARDS.md`.
- Diagnose dropped frames or animation performance: `.agents/skills/animation-performance/SKILL.md`.

Follow the project's existing design tokens and dependencies. Do not add a motion library for simple CSS transitions. Include reduced-motion support and gate hover-only motion for fine pointers. Avoid adding motion to frequent or keyboard-triggered actions unless there is a clear usability reason.
