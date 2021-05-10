# Exercise-2

In this exercise, you'll practice resolving a merge conflict.

> This is a line you will change!

For this exercise, complete the following steps:

1. You should have cloned _this_ repository. Make sure you are
   on the `master` branch, and that all changes are committed.

2. Create and `checkout` a new branch called `danger`

3. On the `danger` branch, use RStudio or another text editor to change
   the above block-quoted line so it contains the word "Warning!"
   Keep it still in a block-quote.

4. `commit` your change with an appropriate commit message.

5. `checkout` the `master` branch again.

6. Now change the above block-quoted line so it contains your favorite
   movie quote. It should still be in a block-quote.

7. `commit` your change with an appropriate commit message.

8. Use `git merge danger` to merge the `danger` branch ___into___ the
   `master` branch. **This should cause a merge conflict**

9. **Don't panic**

10. Use `git status` to confirm that there is a conflict in _README.md`

10. Use RStudio or another text editor to **resolve the merge conflict**
    You will need to make the file look exactly as you want the text
    to appear.  In particular, remove the conflict markers
	`<<<<<<`, `======` and `>>>>>>`.
	You may keep only one version (e.g. the movie quote), or you may
    keep both versions (both _Warning_ and movi quote), or you may put
    something totally different in place of the conflicting lines.

11. When happy with the edits, save the file and
    mark the conflict as resolved with `git
    add README.md`
	
12. Use `git status` to confirm that the conflict is gone.

11. Commit your changes and add a message that you resolved the
    conflict. 

12. Use `git status` to confirm that everything is now merged.



## Cheatsheet:

* create new branch: `git checkout -b <new branch name>`
* switch to an existing branch `git checkout <branch name>`  
  (you have to commit first!)
* what branches are there?  `git branch`  
  the current branch is highlighted
* mark conflict in _file.md_ as resolved: `git add file.md`
