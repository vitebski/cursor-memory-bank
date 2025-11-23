# IMPLEMENT Mode: Code Implementation

## Use When
Writing code, building features, or fixing bugs. (Alias: `/act`)

## Action Sequence
1.  **Acknowledge:** "🔄 Switching to IMPLEMENT Mode..."
2.  **Load Rules:**
    ```javascript
    read_file(".cursor/rules/mode-roles/04-implement-role.mdc")
    read_file(".cursor/rules/isolation_rules/main.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/implement-mode-map.mdc")
    read_file(".cursor/rules/isolation_rules/Core/command-execution.mdc")
    ```
3.  **Load Context:**
    ```javascript
    read_file("memory-bank/tasks.md")
    read_file("memory-bank/activeContext.md")
    read_file("memory-bank/progress.md")
    // If a creative doc exists for this task, read it too
    ```
4.  **Execute:** Follow the process in `implement-mode-map.mdc`.

