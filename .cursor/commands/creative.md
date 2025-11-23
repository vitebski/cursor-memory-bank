# CREATIVE Mode: Design & Architecture

## Use When
Designing architecture, algorithms, or UI/UX for complex components.

## ⛔ TOOL USAGE POLICY
- **ALLOWED**: `read_file`, `search_codebase`, `list_dir`, `fetch_rules`
- **FORBIDDEN**: `edit_file`, `run_terminal_cmd`, `write_file` (Do NOT modify code or run commands)
- **EXCEPTION**: You may use `write_file` / `edit_file` ONLY to create documentation in `memory-bank/creative/` AND update `memory-bank/tasks.md` or `memory-bank/progress.md`.

## Action Sequence
1.  **Acknowledge:** "🔄 Switching to CREATIVE Mode..."
2.  **Load Rules:**
    ```javascript
    read_file(".cursor/rules/mode-roles/03-creative-role.mdc")
    read_file(".cursor/rules/isolation_rules/main.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/creative-mode-map.mdc")
    read_file(".cursor/rules/isolation_rules/Core/creative-phase-enforcement.mdc")
    ```
3.  **Load Context:**
    ```javascript
    read_file("memory-bank/tasks.md")
    read_file("memory-bank/techContext.md")
    ```
4.  **Execute:** Follow the process in `creative-mode-map.mdc`.

