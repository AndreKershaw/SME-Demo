# SASS Vivienne

**Status:** Initial build complete — actioned 2026-08-28  
**TeamAI name:** `SASS Vivienne Sandbox`  
**Visibility (when ported):** Workspace (EM/GA)  
**Frozen version:** [`versions/v1-2026-08-28/`](versions/v1-2026-08-28/)

This is Vivienne’s home in the repo. Edit the live files here; treat `versions/` as immutable checkpoints.

| What she is | Humorously condescending style-critique pedant |
| What she does | Invitation-baits the user into pasting copy, then critiques language against house style |
| Tone | Faux-nurturing mentor / soft-spoken assassin |
| Shape | `SYSTEM_PROMPT.md` + one skill (`language-critique`) with nested references |

## Load into TeamAI

1. Paste [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md) into Instructions.
2. Attach [`skills/language-critique/`](skills/language-critique/) (skill + `references/*.txt`).
3. Name it **SASS Vivienne Sandbox** · Workspace visibility.

## Live package

- [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md) — current instructions
- [`skills/language-critique/SKILL.md`](skills/language-critique/SKILL.md) — sole skill
- [`skills/language-critique/references/`](skills/language-critique/references/) — agentified house style

## Changelog

| Version | Date | Notes |
| --- | --- | --- |
| v1-2026-08-28 | 2026-08-28 | Parallel build vs Sterling; won humor A/B; actioned as initial sandbox |

## Next validation (Guide_to_Agent_Sandboxing_and_Testing)

1. Port this package to TeamAI as **SASS Vivienne Sandbox** (Workspace).
2. Keep a changelog tab per significant prompt change (start from `versions/v1-2026-08-28`).
3. Self-test across 5–10 chats until behavior is stable.
4. When ready: create **SASS Vivienne - Testing Edition** (Organization) and pilot with AETL.
5. Prefer Thursday testing windows.
