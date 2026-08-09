# Workflow — DISCOVER

## Goal

Identify a small number of genuinely worthwhile technical stories from current developments.

Discovery is not writing.

## Inputs

- `sources/`
- existing `queue/`
- recent official announcements
- release notes/changelogs
- research papers
- security advisories
- meaningful repository releases
- high-quality secondary reporting as discovery input

## Procedure

1. Define the discovery window (for example last 24 hours).
2. Review the highest-value primary source surfaces for each beat.
3. Capture only potentially relevant events in `queue/signals.md`.
4. Deduplicate the same underlying event.
5. For each signal, identify at least one primary source when available.
6. Score viable signals using `queue/candidates.md`.
7. Propose an information-gain angle.
8. Reject items that would only support a generic rewrite.
9. Return the top candidates to the human editor.

## Story selection questions

- What actually changed?
- Is the change technically meaningful?
- Who should care?
- Is primary evidence available?
- Can we produce a comparison, calculation, dataset, or technical interpretation?
- Are we early enough that publishing has value?
- Would the piece remain useful after the initial news cycle?

## Output

Update:
- `queue/signals.md`
- `queue/candidates.md`

Do NOT:
- move anything into `queue/approved.md`;
- create a publishable article;
- invent a thesis before research.

The human editor selects the story.
