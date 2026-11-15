---
name: using-superpowers
description: Use when starting any conversation - explains when a superpowers skill applies and how skills fit together; use a skill when the task clearly matches it, not on every response
---

<SUBAGENT-STOP>
If you were dispatched as a subagent to execute a specific task, ignore this skill.
</SUBAGENT-STOP>

## The Rule

**Use a skill when the task clearly matches its description, or when your human partner asks for it by name.** Check before substantive work — building, debugging, planning, reviewing — because process skills shape how that work goes, so they belong at the start, not halfway through.

**Answer directly when no skill clearly fits.** Questions, lookups, conversation and small self-contained edits don't need a skill check. Don't invoke a skill just in case.

**Before entering plan mode:** if you haven't already brainstormed, invoke the brainstorming skill first.

Once you've chosen a skill, follow it. If it has a checklist, create a todo per item. If it turns out wrong for the situation, drop it.

## Skill Priority

When multiple skills apply, process skills come first — they set the approach, then implementation skills (frontend-design, etc.) carry it out. Brainstorming and systematic-debugging are Superpowers' most common process skills, but the rule holds for any of them.

- "Let's build X" → superpowers:brainstorming first, then implementation skills.
- "Fix this bug" → superpowers:systematic-debugging first, then domain skills.

## Platform Adaptation

If your harness appears here, read its reference file for special instructions:

- Claude Code: `references/claude-code-tools.md`
- Codex: `references/codex-tools.md`
- Pi: `references/pi-tools.md`
- Antigravity: `references/antigravity-tools.md`
- Hermes Agent: `references/hermes-tools.md`
- Muse: `references/muse-tools.md`

## User Instructions

User instructions (CLAUDE.md, AGENTS.md, GEMINI.md, etc, direct requests) take precedence over skills, which in turn override default behavior. Only skip skill workflows or instructions when your human partner has explicitly told you to.
