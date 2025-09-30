# Creating notes

Open file feature created

{
    ".": [
        "General.md",
        "notes2.md"
    ],
    "hidden": [
        "general.md"
    ],
    "test-folder": [
        "test.md"
    ],
    "hidden/nested": [
        "nested.md"
    ]
}

# Custom commands
- [ ] Big refactor for /utils/system 
    - [ ] Remove vscode and all validation must be done outside
- [X] Fix order folder first before files
- [X] Refactor command executor
- [X] Update name command functionality
    - [X] Add regex testing to disable special characters
    - [X] Check if file exist - then do not rename
- [ ] Delete command functionality 
    - [X] Add confirm
    - [X] Update action to Delete/Delete file
- [ ] Create command
    - [X] Create note
    - [ ] Create folder
- [ ] Refresh command functionality 
    - [ ] Refresh command on every CUD action
        - [ ] Create action
        - [ ] Update action 
        - [ ] Delete action 
