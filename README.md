
# Git Cheat Sheet

User Commands for Git

1. Initialize a Git Repository:
   ```bash
   git init
   ```

2. Check Git Repository Status:
   ```bash
   git status
   ```

3. Add Files to Staging Area:
   ```bash
   git add --all
   ```

4. Commit Changes:
   ```bash
   git commit -m "Initial commit"
   ```

5. Commit Modified Files:
   ```bash
   git add <file_name>
   git commit -m "Message"
   ```

6. Remove Git Repository:
   ```bash
   rm -rf .git
   ```

7. Clone a Git Repository:
   ```bash
   git clone <repository_url>
   ```

8. Print Working Directory:
   ```bash
   pwd
   ```

9. List Files in Directory:
   ```bash
   ls
   ```

10. Change Directory:
    ```bash
    cd <directory_name>
    ```

11. Create a New File:
    ```bash
    touch error.log
    ```

12. Ignore Files (using .gitignore):
    Create a `.gitignore` file and specify files/directories to ignore.

13. Unstage a File:
    ```bash
    git rm --cached <file_name>
    ```

14. Create `.gitignore` File:
    ```bash
    touch .gitignore
    ```

15. View Difference (Between Working Directory and Staging Area):
    ```bash
    git diff
    ```

16. View Difference (Between Staging Area and Last Commit):
    ```bash
    git diff --staged
    ```

17. Commit All Modified Files Directly:
    ```bash
    git commit -a -m "Direct commit"
    ```

18. Remove a File:
    ```bash
    git rm <file_name>
    ```

19. Rename a File:
    ```bash
    git mv <old_file_name> <new_file_name>
    ```

20. View Commit History:
    ```bash
    git log
    ```

21. View Compact Commit History:
    ```bash
    git log --oneline
    ```

22. Show Changes in Commit:
    ```bash
    git log -p
    ```

23. Show Commit with Stats:
    ```bash
    git log --stat
    ```

24. Show Full Commit Details:
    ```bash
    git log --full
    ```

25. Show Commits Since a Specific Time:
    ```bash
    git log --since="2 days ago"
    ```

26. View Author of Commits:
    ```bash
    git log --pretty=format:"%h -- %an"
    ```

27. Amend the Last Commit:
    ```bash
    git commit --amend
    ```

28. Unstage a Staged File:
    ```bash
    git restore --staged <file_name>
    ```

29. Revert Working Directory to Last Commit (for unstaged files):
    ```bash
    git checkout -- <file_name>
    ```

30. Revert Entire Working Directory to Last Commit (for all files):
    ```bash
    git checkout -f
    ```

31. Set Remote Repository URL:
    ```bash
    git remote add origin <repository_url>
    ```

32. Push Commits to Remote Repository:
    ```bash
    git push -u origin master
    ```

33. Configure Git Aliases:
    ```bash
    git config --global alias.st status
    ```

34. Discard All Changes in Working Directory:
    ```bash
    git restore <file_name>
    ```

35. Create and Switch to a New Branch:
    ```bash
    git checkout -b develop
    ```

36. Switch to the Master Branch:
    ```bash
    git checkout master
    ```

37. Merge a Branch into Master:
    ```bash
    git merge <branch_name>
    ```

38. List Branches:
    ```bash
    git branch
    ```

39. List Branches with Commit Details:
    ```bash
    git branch -v
    ```

40. Show Merged Branches:
    ```bash
    git branch --merged
    ```

41. Show Unmerged Branches:
    ```bash
    git branch --no-merged
    ```

42. Delete a Branch (if merged):
    ```bash
    git branch -d <branch_name>
    ```

43. Force Delete a Branch (even if not merged):
    ```bash
    git branch -D <branch_name>
    ```

44. Quit Vim Editor:
    Press `Esc` key, then type `:wq` and press `Enter`.

45. Shortcut for Pushing to a Branch:
    ```bash
    git push <branch_name>
    ```

46. Change Branch Name on Remote Repository:
    ```bash
    git push <branch_name>:<new_branch_name>
    ```

47. Show Remote Repository URL:
    ```bash
    git remote -v
    ```

48. Restore a Staged File:
    ```bash
    git restore --staged <file_name>
    ```

49. Display Help Information:
    ```bash
    git help
    ```

