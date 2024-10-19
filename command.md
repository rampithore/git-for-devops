# Command Overview

This file contains a series of Git commands and their explanations.

1. Create files:
   - `mkdir hello.txt hello-1.txt`: Create two files named hello.txt and hello-1.txt.

2. List files in the current directory:
   - `ls`: Show the files and directories.

3. Check Git status:
   - `git status`: Display the state of the working directory and staging area.

4. Remove files:
   - `rm hello-1.txt hello.txt`: Delete the files hello-1.txt and hello.txt.
   - `rmdir hello-1.txt hello.txt`: Remove directories (will fail if the files are not directories).

5. Create a new file:
   - `touch hello.txt`: Update the timestamp of hello.txt or create it if it doesn’t exist.

6. Add files to Git staging:
   - `git add hello.txt`: Stage hello.txt for the next commit.

7. Commit changes:
   - `git commit -m "first commit"`: Save changes with a message describing the commit.

8. Create and edit a file:
   - `touch la.txt`: Create la.txt.
   - `vim la.txt`: Open la.txt in the Vim editor.

9. Stage and commit the new file:
   - `git add la.txt`: Stage la.txt for the next commit.
   - `git commit -m "la added"`: Commit the changes to la.txt.

10. Remove a file:
    - `rm la.txt`: Delete la.txt.

11. Restore a file from the last commit:
    - `git restore la.txt`: Restore la.txt to its last committed state.

12. Create multiple new files:
    - `touch file file2 file3`: Create three new files named file, file2, and file3.

13. Add all changes to staging:
    - `git add .`: Stage all modified and new files.

14. Commit all changes:
    - `git commit -m "new files"`: Commit all staged changes with a message.

15. Clear the terminal:
    - `clear`: Clear the terminal screen.

16. View Git logs:
    - `git log`: Show the commit history.

17. Branching:
    - `git checkout -b dev`: Create and switch to a new branch named dev.
    - `git checkout master`: Switch back to the master branch.
    - `git checkout dev`: Switch to the dev branch.
    - `git branch`: List all branches.

18. Add and commit a new file (olo.txt):
    - `touch olo.txt`: Create olo.txt.
    - `git add olo.txt`: Stage olo.txt.
    - `git commit -m "added olo"`: Commit olo.txt.

19. View the commit history in a simplified format:
    - `git log --oneline`: Show the commit history with one line per commit.

20. View command history:
    - `history`: Display a list of commands that were run.

This concludes the command overview. Use these commands to manage files and track changes with Git.
