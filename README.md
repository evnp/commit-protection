Commit Protection
================

After a mishap with accidentally committing code I had commented for test purposes, I decided this would be useful. It's a git pre-commit hook that lets you mark any line with DO_NOT_COMMIT (in a comment) and will prevent these lines from being committed until you remove the flag. Just drop it into <repository>/.git/hooks to use it. You'll probably have to make the file executable for it to work.
