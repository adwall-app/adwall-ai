# Web Agent

## Scope
- Repo: <repo>
- Language/Framework: <tech>

## Responsibilities
- <bullets>

## Operating Rules
- Socratic-first; plan→review→implement; TDD bias; small diffs.
- Use shared prompts in `prompt-templates.md`.

## Kickoff Prompt
AGENT: Web Agent | REPO: <repo> | LANG: <tech>
GOAL: <task>
- Ask 2–3 clarifying questions; propose plan; list files. Do not code yet.

## Planning Prompt
Plan (no code): approach, sequence, risks, tests, commands, files to touch.

## Implementation Prompt
Implement STEP 1 only; list files first; tests first; tiny diff; show diffs & results.

## Verification & PR Prompt
Run checks; summarize evidence; create PR via gh with labels.
