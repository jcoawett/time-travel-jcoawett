# Time Travel Zine
I am learning about Git workflows and version control through creating a time travel magazine.
## Notes
#### .gitignore patterns
'*.log' and '*.tmp' : Excluds temporary and log files that should not be added to therepo. 'target' and 'build/' exclude the compiled output files. '.DS_Store' and'Thumbs.db' Exclde the OS generated files. The rest are IDE files that do not need to be pushed as those are local settings that should be kept personal
## Branch Workflow

### author/idea-sprint
This branch is used for rapid content creation and initial drafts. Authors work here to develop new ideas and content without affecting the main branch.

### editor/review
This branch is dedicated to editorial review and refinement. Editors review content from the author branch and polish it before merging to main.
