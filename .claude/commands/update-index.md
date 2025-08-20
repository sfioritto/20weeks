---
description: Update index.md with current week's progress from logs
---

Read the current week's log file from @logs/ (named after Monday's date) and regenerate @index.md with:

1. Note today's date from the environment context to understand what day of the week it is
2. Calculate current week's progress from the log entries (only count COMPLETED days, not including today)
3. Generate a weekly summary paragraph following the guidelines in @docs/weekly-summary-guidelines.md
   - Include specific step/calorie recovery needs in the summary when significantly off target
   - For steps: If below 4900 average, include "need X steps per day for remaining days" in the summary
   - For calories: If above 1950 average, include "need X calories per day for remaining days" in the summary
   - Sleep: Only mention if disrupted multiple nights (shows pattern of tiredness). If so, add gentle reminder about "even one set counts, 15-minute run is fine, you can nap"
   - Don't mention single sleep disruptions - they're normal
4. Update all required goals (runs, lifts, calories, steps) with current counts and WEEKLY AVERAGES
   - Steps: 4900-5100 average all count as meeting the goal. Only flag if outside this range
   - Calories: 1950 or below average is acceptable. Only flag if above 1950
   - Don't worry about small daily variations (50 calories, 200 steps) - focus on significant deviations
5. Update bonus goals (protein, fiber, bedtime)
   - Protein: 185g+ counts as hitting 190g goal (within 5g under is close enough). Note as "188g (close enough)" when applicable
   - Fiber: 26g+ counts as hitting 30g goal (within 4g is close enough). Note as "27g (close enough)" when applicable
   - Show progress as "X/Y days (X/7 for week)" showing both completed days progress and weekly total
   - For today's incomplete entries, note as "Today: Not logged yet" rather than assuming they missed it
6. Set appropriate week status
7. Provide focused action items in "This Week's Focus" section

Follow the weekly summary guidelines exactly as specified in @docs/weekly-summary-guidelines.md

Write the complete updated index.md file.