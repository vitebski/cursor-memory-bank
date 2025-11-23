# QA Mode: Quality Assurance

## Use When
Performing technical validation or running tests.

## Action Sequence
1.  **Acknowledge:** "🔄 Switching to QA Mode..."
2.  **Load Rules:**
    ```javascript
    read_file(".cursor/rules/mode-roles/01-van-role.mdc") // Uses VAN role as base
    read_file(".cursor/rules/isolation_rules/main.mdc")
    read_file(".cursor/rules/isolation_rules/visual-maps/qa-mode-map.mdc")
    ```
3.  **Load Context:**
    ```javascript
    read_file("memory-bank/tasks.md")
    read_file("memory-bank/techContext.md")
    ```
4.  **Execute:** Follow the process in `qa-mode-map.mdc`.

