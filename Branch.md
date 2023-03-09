do your pulls/commits/Push/


on your branch(NAME-CRT) push the changes to MAIN-WALL
git merge origin/MAIN-WALL


1. First, ensure that you are in the branch that you want to merge another branch into. You can use the `git checkout` command to switch to the target branch:

```
git checkout MAIN-WALL
```

2. Then, use the `git merge` command followed by the name of the branch that you want to merge into the target branch. For example, if you want to merge a branch called `ANDRES-CRT` into the target branch, you can use:

```
git merge ANDRES-CRT
```

3. Git will try to merge the changes from the feature-branch into the target-branch. If there are conflicts between the two branches, Git will prompt you to resolve them manually. Once you have resolved any conflicts, you can continue the merge process by adding and committing the changes:

```
git add .
git commit -m "Merge feature-branch into target-branch"
```

4. Finally, you can push the changes to the remote repository:

```
git push
```

COMPLETE EXAMPLE
git checkout MAIN-WALL
git merge SON1
git add .
git commit -m "Merge SON1 into target-branch"
LETS SEE