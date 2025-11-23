# REFLECT Mode: Review & Archive

## Use When
Verifying completed work and archiving tasks.

## Action Sequence
1.  **Acknowledge:** "🔄 Switching to REFLECT Mode..."
2.  **Load Rules:**
    ```javascript
    read_file(".cursor/rules/mode-roles/05-reflect-role.mdc")
    read_file(".cursor/rules/isolation_rules/main.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/reflect-mode-map.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/archive-mode-map.mdc")
    ```
3.  **Load Context:**
    ```javascript
    read_file("memory-bank/tasks.md")
    read_file("memory-bank/progress.md")
    ```
4.  **Execute:** Follow the process in `reflect-mode-map.mdc`.

