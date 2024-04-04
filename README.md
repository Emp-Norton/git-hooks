# git-hooks
Just a little stash of useful hooks. scripts. whatever else I find comes in handy.


Create a file in the root directory for the project to setup project-specific environment variables. The prepare-commit-msg hook depends on this file to grep for the appropriate name, rather than dealing with conflicting globals.
The script will then grep for the 'PROJECT_NAME' key-value pair in said file, and set that in the commit message alongside the date.
