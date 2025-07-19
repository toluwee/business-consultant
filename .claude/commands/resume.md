## RESUME Workflow: Reload Last Saved State

This command restores Claude’s memory from the last THINK → PLAN → ACT cycle.

### Steps:
1. Load:
   - `@logs/think.md`
   - `@logs/plan.md`
   - `@logs/act.md`
2. Summarize current state
3. Ask user: “Would you like to continue from here?”

### Purpose:
- Recover from timeouts or credit loss
- Maintain continuity across sessions
- Avoid redoing previous work

### Output:
- Summary of last saved state
- Optional next steps or continuation prompt
