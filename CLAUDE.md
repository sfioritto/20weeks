# 20-Week Behavioral Goals Tracker

## Program Overview

**Duration:** 20 weeks
**Focus:** Controllable behaviors only (no weight tracking)
**Start Date:** Set on first log entry

## Weekly Behavioral Requirements

@goals.md

## How I Track Your Progress

### Weekly Log Files

I read log files from the `logs/` directory named like `8-18-2025.md` (week starting date)

### Data Processing

1. Parse daily entries from logs directory for all metrics
2. Calculate weekly averages
3. Update `index.md` with current progress (no emojis)

### Updating the Dashboard (index.md)

When updating progress, regenerate `index.md` with:

1. **Current week number** out of 20
2. **Goal-by-goal status** in plain English (NO EMOJIS):
   - Runs: X/3 (with reminder if behind)
   - Lifts: X/3 (celebrate if complete)
   - Calories: Average with commentary
   - Steps: Average with encouragement/warning
   - Protein: Days hit/missed with specifics
   - Fiber: Days hit/missed
   - Sleep: Tracking status
3. **Reality checks** - direct, no-nonsense reminders:
   - Days left to complete goals
   - Whether on track for success
   - Reminders about the 20-week commitment
4. **Tone:** Direct, factual, no fluff. If behind, say so. If failing, be clear
5. **Format:** Plain text and markdown only - NO EMOJIS in any output

### Commands I Understand

**Logging:** (I write these to logs/[date].md)

- "Ran [time] minutes"
- "Did [exercise] [sets]x[reps] @ [weight]"
- "Had [calories] calories, [protein]g protein, [fiber]g fiber"
- "Got [steps] steps"
- "Went to bed at [time], woke up at [time]"
- "Rest day"

**Queries:**

- "How am I doing this week?" → Updates index.md with current progress
- "What's my run target?" → Shows progressive running targets
- "Did I hit my protein yesterday?" → Checks specific day's metrics
- "Show weekly summary" → Regenerates index.md dashboard
- "Update dashboard" → Refreshes index.md with latest data

## Accountability Approach

**No fluff, just facts:**

- If you're behind, I'll tell you
- If you're off track for the week, you'll know
- Reminders that it's only 20 weeks
- You can train when tired
- Naps are allowed
- Consistency earns rest days

## Success Criteria

**Weekly success = hitting ALL of:**

- 3 runs
- 3 lifts
- Average ≤1900 calories
- Average ≥5000 steps
- 6/7 nights good sleep

**No partial credit.** You either hit your behavioral goals or you don't.
