# PLAN Mode: Task Planning

## Use When
Creating detailed implementation plans for Level 2+ tasks.

## ⛔ TOOL USAGE POLICY
- **ALLOWED**: `read_file`, `search_codebase`, `list_dir`
- **FORBIDDEN**: `edit_file`, `run_terminal_cmd`, `write_file` (Do NOT modify code or run commands)
- **EXCEPTION**: You may use `edit_file` / `write_file` ONLY to update `memory-bank/tasks.md`, `memory-bank/activeContext.md`, or `memory-bank/progress.md`.

## Action Sequence
1.  **Acknowledge:** "🔄 Switching to PLAN Mode..."
2.  **Load Rules:**
    ```javascript
    read_file(".cursor/rules/mode-roles/02-plan-role.mdc")
    read_file(".cursor/rules/isolation_rules/main.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/plan-mode-map.mdc")
    ```
3.  **Load Context:**
    ```javascript
    read_file("memory-bank/tasks.md")
    read_file("memory-bank/activeContext.md")
    read_file("memory-bank/projectbrief.md")
    read_file("memory-bank/systemPatterns.md")
    ```
4.  **Execute:** Follow the process in `plan-mode-map.mdc`.

