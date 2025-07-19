## SOLVE Workflow: Think → Plan → Act

This command runs a full problem-solving cycle using structured reasoning.

### Steps:
1. Run `/project:think`
   - Save output to `logs/think.md`
2. Run `/project:plan`
   - Save output to `logs/plan.md`
3. Run `/project:act`
   - Save output to `logs/act.md`

### Purpose:
- Ensure Claude reflects before acting
- Persist each phase to disk for recovery
- Reduce hallucinations and improve traceability

### Output:
- `logs/think.md`: Problem analysis and options
- `logs/plan.md`: Strategy and steps
- `logs/act.md`: Execution log and results

Use this when tackling complex tasks or multi-step implementations.
