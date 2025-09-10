---
description: Update index.md with current week's progress from logs
---

First read the @goals.md file to understand my goals for this program.

Read the current week's log file from @logs/ (named after Monday's date).

Then you're going to regenerate @index.md with the following steps:

1. Note today's date from the environment context to understand what day of the week it is, assuming you get some kind of UTC time convert it to Central Time.
2. **CRITICAL: Check for rest day usage FIRST**
   - A rest day is ANY day where NEITHER a run NOR a lift was logged
   - Look through each completed day (Monday through yesterday) in the current week's log
   - If you find a day with no run AND no lift, that's when the rest day was used
   - Example: If Monday has steps, calories, protein but NO run and NO lift = Monday was the rest day
3. Calculate current week's progress from the log entries (only count COMPLETED days, not including today)
4. Generate a weekly summary paragraph following the guidelines in @docs/weekly-summary-guidelines.md
   - MUST include rest day status: If used, state which day it was used and note they need daily workouts to avoid doubling up
   - If rest day not yet used, mention they have flexibility
   - Include specific step/calorie recovery needs in the summary when significantly off target
   - For steps: If below 4900 average, include "need X steps per day for remaining days" in the summary
   - For calories: If above 1950 average, include "need X calories per day for remaining days" in the summary
   - Sleep: Only mention if disrupted multiple nights (shows pattern of tiredness). If so, add gentle reminder about "even one set counts, 15-minute run is fine, you can nap"
   - Don't mention single sleep disruptions - they're normal
5. Update all goals
   - Include current week's run target duration (calculate using Week N = 16.5 × (1.0221)^(N-1) minutes)
   - Show runs, lifts, calories, steps with current counts and WEEKLY AVERAGES
   - Steps: 4900-5100 average all count as meeting the goal. Only flag if outside this range
   - Calories: 1950 or below average is acceptable. Only flag if above 1950 and calculate how many calories per day you need to hit the goal.
   - Don't worry about small daily variations (50 calories, 200 steps) - focus on significant deviations
6. Update bonus goals (protein, fiber, bedtime)
   - Protein: 185g+ counts as hitting 190g goal (within 5g under is close enough). Note as "188g (close enough)" when applicable
   - Fiber: 26g+ counts as hitting 30g goal (within 4g is close enough). Note as "27g (close enough)" when applicable
   - Show progress as "X/Y days (X/7 for week)" showing both completed days progress and weekly total
   - For today's incomplete entries, note as "Today: Not logged yet" rather than assuming they missed it
7. Set appropriate week status
8. Provide focused action items in "This Week's Focus" section
9. Add "Next Lift Day" section at the bottom

   - Determine which lifting day is next in the rotation (Day 1: Lower Focus, Day 2: Upper Focus, Day 3: Full Body)
   - Look at current and previous week's logs to find the most recent lifting day
   - Based on the rotation, identify the next day's main lift:
     - Day 1: "Squat Day" (Back Squat is the main lift)
     - Day 2: "Bench Day" (Bench Press is the main lift)  
     - Day 3: "Deadlift Day" (Deadlift is the main lift)
   - Format as:

     ```
     ## Next Lift Day

     **[Squat/Bench/Deadlift] Day** - [View full workout](lifting.html)

     Remember: Even completing one set of each exercise counts as a lifting session if you're exhausted.
     ```

10. Update lifting.html with current lifting cycle week
    - The lifting program runs on 4-week cycles (Week 1-4, then repeats)
    - Determine current lifting week by tracking workout completion:
      - Look at the log files to count how many complete lifting weeks have been done
      - A lifting week is complete when all 3 lifting days (Day 1, Day 2, Day 3) are done
      - When starting a new lifting day after completing all 3 days = advance to next week
      - After Week 4, cycle back to Week 1
    - Example: If you just finished Day 3 of Week 2 and log Day 1 again, you're now in Week 3
    - Update the "Current: Week X of 4-week cycle" in lifting.html based on this tracking

Follow the weekly summary guidelines exactly as specified in @docs/weekly-summary-guidelines.md

Write the complete updated index.md file.
