# Git Lab Assignment - TASK 7: Reflection

## Student Information
* **Name:** NUR ALYAA QISTINA BINTI MOHD DZULKARNAIN
* **Matric Number:** 251594283

------------------------------------------------------------------------------------------------------------------------------------------

## 1. Understanding Merge Conflicts
**What causes merge conflicts?**
Merge conflicts occur when Git is unable to automatically resolve differences in code between two commits. This usually happens when two people (or two branches) modify the **exact same line** in a file, or when one person deletes a file while another is modifying it. Git gets "confused" and asks the user to manually decide which version to keep.

**How I resolved it:**
1. I identified the file with the conflict (`profile.txt`) after running `git merge`.
2. I opened the file in a text editor (Notepad) and located the conflict markers: `<<<<<<<`, `=======`, and `>>>>>>>`.
3. I manually edited the file by removing the markers and choosing the correct content (Hobby: Coding).
4. I saved the file, then used `git add profile.txt` to stage the resolution.
5. Finally, I ran `git commit` to finalize the merge.

------------------------------------------------------------------------------------------------------------------------------------------

## 2. Reflection (Task 7)

### What I Learned
Through this assignment, I learned how to manage versions of my work effectively. I now understand how to use branches to work on new features without breaking the main project and how to collaborate using Pull Requests on GitHub.

### Challenges Faced
The biggest challenge was understanding why a merge conflict occurs. At first, I struggled to trigger the conflict because I was editing different lines. I also faced a 'pathspec' error early on because I forgot to create the file before adding it to Git.

### How Git Helps in Real Projects
In real-world industry projects:
* **Collaboration:** Many developers can work on the same codebase simultaneously using branches.
* **Safety:** If a mistake is made, we can easily revert to a previous working version.
* **Accountability:** Through `git log`, we can see exactly who made what changes and when.

------------------------------------------------------------------------------------------------------------------------------------------