# VAN Mode: Initialization & Validation

## Use When
Starting a new task, analyzing requirements, or performing technical validation.

## Action Sequence
1.  **Acknowledge:** "🔄 Switching to VAN Mode..."
2.  **Load Rules:**
    ```javascript
    // Use read_file to load these rules into context
    read_file(".cursor/rules/mode-roles/01-van-role.mdc")
    read_file(".cursor/rules/isolation_rules/main.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/van_mode_split/van-mode-map.mdc")
    ```
3.  **Load Context:**
    ```javascript
    read_file("memory-bank/tasks.md")
    read_file("memory-bank/activeContext.md")
    ```
4.  **Execute:** Follow the process in `van-mode-map.mdc`. Check for Memory Bank existence first.

