# git state
   1. working directory/workspace(git init)
            |
    git status   git add .
            |
            @
   2. staging area/index
            | git log --oneline
   git log   git commit -m "message" git reset --soft HEAD^
   git diff |
            @
   3. local repository
   4. remote repository

## <---------------------------------------------------------------------------------->

## working directory @--- git reset HEAD^ --- local repository
## staging area @--- git reset -soft HEAD^ --- local repository
## outside @--- git reset --hard HEAD^ --- local repository
## Deleting number of commits
   - git reset -soft HEAD~2
   - git reset -soft HEAD~3
# git checkout commit_id/HEAD~Number(save using)

## git show commit_id/ git show/ git show HEAD~Number
## git revert
## git clean
## git rm
## git checkout master(remove previous position)

## <---------------------------------------------------------------------------------->

 ##  .gitignore -----> text.txt
                        .env
                        *.txt
                        !main.txt
                        test?.txt[test1.txt, test2.txt(?=1,2,3...)]
                        temp/


## <---------------------------------------------------------------------------------->