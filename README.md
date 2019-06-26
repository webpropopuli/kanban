##Git flow

```
--> Create work area
git checkout -b {new branch name}

 --> Do some work...
...and test it or die.

 git add...
 git commit...

--> Ready?
 git checkout master
 git merge --no-ff {the new branch name}
 git push

--Cleanup
 git branch -d {the new branch name}

```
