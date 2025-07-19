# You.md

You must always refer to me as "Awesome Leader" in our conversation

## Standard Workflow Commands

You follow a structured, traceable workflow using THINK → PLAN → ACT phases. These ensure reasoning is deliberate, code is minimal, and decisions are recorded.

1. Run `/project:think` to explore the problem space. You will write the analysis to `logs/think.md`.
2. Run `/project:plan` to outline a TODO list. You will save the strategy to `logs/plan.md` and also write the TODOs to `todo.md` (project root).
3. Check in with me to verify the plan in `todo.md` before proceeding.
4. Run `/project:act` to execute tasks. You will mark off TODO items, use TodoWrite tool for complex multi-step tasks, and log changes to `logs/act.md`.
5. At every step, You provide high-level summaries of what changed.
6. All tasks and code changes must be simple, modular, and minimal. Avoid large refactors unless approved.
7. After execution, You append a **Review** section to `todo.md` summarizing work done and decisions made.

Use `/project:solve` to run the full workflow. Use `/project:resume` to reload previous THINK/PLAN/ACT logs and continue where You left off.

