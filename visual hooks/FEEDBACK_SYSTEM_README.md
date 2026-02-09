# Visual Hooks — Feedback System Overview

## What Is This?
A self-learning feedback loop that makes every hook I generate sharper than the last. Your feedback is stored, distilled into rules, and applied automatically — even across new conversations.

---

## Where Do The Files Live?

All memory files are stored at:
```
/Users/syedibrahim/.claude/projects/-Users-syedibrahim-Desktop-visual-hooks/memory/
```

---

## The 6 Files — What Each One Does

### 1. MEMORY.md — The Master Brain
**What it is:** The instruction file that gets auto-loaded into every new conversation.
**What's inside:**
- Core instruction: "Read the Pattern Interrupt Playbook for every hook request"
- The 12 success principles + 10 failure modes (summarized)
- The feedback loop workflow (step-by-step)
- Links to all other files
**You touch this?** No — this is my operating system. It runs in the background.

---

### 2. hook_feedback.md — Your Raw Feedback Log
**What it is:** Every piece of feedback you give me, logged word-for-word under the exact hook it refers to.
**What's inside:**
- Organized by Batch → Script → Hook
- Each hook has: name, mechanism (short description), status, and your raw feedback
- Status options: Awaiting feedback / Approved / Rejected / Modify
- A "Patterns Detected" section at the bottom that tracks what you consistently like/dislike
**Current state:** 29 hooks logged, all awaiting your feedback.
**You touch this?** No — I update it when you give feedback. But you can read it anytime.

---

### 3. hook_preferences.md — The Rules Engine
**What it is:** Distilled rules extracted from your feedback patterns. These become HARD CONSTRAINTS on every future hook.
**What's inside:**
- Creator profile (you: Syed Ibrahim, 2XG, Hindi + Street Kannada)
- Formats to ALWAYS AVOID (talking head + bold text, guru style)
- Style preferences (visual, tone, text, audio) — filled as feedback comes in
- Production constraints (cross-referenced from production_context.md)
- Tables: "What Works" and "What Doesn't Work" with your exact words
- Derived rules with confidence levels (High/Medium/Low)
**Current state:** Base constraints set. Preferences sections waiting for your feedback to fill them.
**You touch this?** No — I distill your feedback into rules here. But you can read it to see what rules are active.

---

### 4. hook_library.md — The Master Hook Catalog
**What it is:** Every hook ever generated, organized in tables with status tracking.
**What's inside:**
- Organized by Batch → Script
- Each hook has: unique ID, name, mechanism, type (new/existing), status, recommendation
- Status lifecycle: Generated → Feedback Received → Approved/Rejected/Modified → Shot → Published → Performance Data
- Performance tracker table (for after hooks go live — views, hook rate, retention)
- Stats: Total hooks generated, approved, rejected, published
**Current state:** 29 hooks across 6 scripts. 2 rejected (by playbook evaluation). 27 awaiting your feedback.
**You touch this?** No — I maintain it. But it's your single source of truth for "what hooks exist."

---

### 5. production_context.md — What You Can Actually Shoot
**What it is:** Documents your cast, locations, equipment, and production limits so I never propose a hook you can't execute.
**What's inside:**
- Cast: Syed Bhai (always available), Real Father, Real Amma, Real Son (available for BCH/Doodle scripts)
- Locations: BCH Store (primary)
- Equipment: (needs your input — camera, lighting, audio gear)
- Props available: Doodle cycle, helmet, reflectors, phone, etc.
- What's easy vs. difficult vs. not feasible to shoot
- Brand guidelines for 2XG and BCH
**Current state:** Partially filled from what I know. NEEDS YOUR INPUT on equipment, additional locations, and what's feasible.
**You touch this?** YES — tell me about your equipment, shooting constraints, and I'll update it. This directly affects what hooks I propose.

---

### 6. playbook_quick_ref.md — The Cheat Sheet
**What it is:** A condensed version of the full Pattern Interrupt Hook Master Playbook, designed for fast reference.
**What's inside:**
- The 3-stage neurological chain (Orienting Response → Prediction Error → Curiosity Gap)
- All 12 success principles in a table with core questions and quick tests
- All 10 failure modes in a table with diagnostic signals
- Role-based lens summary (Videographer / Editor / Creator)
- Commoditized formats to avoid in YOUR niche (specific to Indian business content)
- Golden rules from the playbook
**You touch this?** No — this is my quick-access reference. But you can read it to see the framework I apply to every hook.

---

## How The Loop Works

```
YOU: "Give me hooks for this script"
         ↓
ME: Read preferences + feedback + production context
         ↓
ME: Generate hooks (all rules applied)
         ↓
YOU: "Hook 2 is fire. Hook 4 feels too produced. Hook 1 is meh."
         ↓
ME: Log exact feedback in hook_feedback.md
    Update status in hook_library.md
         ↓
ME: Spot pattern → "He prefers raw/shootable over VFX-heavy"
    Add rule to hook_preferences.md
         ↓
NEXT ROUND: Hooks are automatically sharper
         ↓
REPEAT — system compounds over time
```

---

## Current Stats

| Metric | Count |
|---|---|
| Total hooks generated | 29 |
| Scripts covered | 6 (Scripts 1-5 + Amma's Control Panel) |
| Hooks approved | 0 (awaiting feedback) |
| Hooks rejected | 2 (by playbook evaluation) |
| Feedback rounds completed | 0 |
| Preference rules active | 2 (avoid talking head + bold text, avoid guru style) |

---

## What I Need From You

1. **Feedback on the 27 hooks** — even quick one-liners per hook help ("yes", "no", "too complex", "love this", "change X")
2. **Production details** — What camera do you shoot on? What lighting? What editing software? This helps me keep hooks shootable.
3. **Performance data** (after publishing) — Views, hook rate, 3-second retention. This closes the loop between theory and reality.

---

*This file is a read-only overview. The actual system files live in the `.claude` memory directory and are updated automatically during our conversations.*
