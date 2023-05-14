# bundle-1

- Create a project & initialize git(from my github account)
- Rename your main branch from `master` to `main`(my default branch is set to main)
- Make changes to the project (updated this readme)
- Stage your changes and commit them(did git add .)
- Create a github repo and connect it with your project(cloned this repo from this (link)[https://github.com/divinecharlotte/bundle-1.git])
- Push your changes to github(did git push )
- Create a new branch `dev`(git checkout -b dev)
- From `dev` create another branch `test`(checked out to dev branch and created test from it)
- Go back to the `dev` branch and delete the `test` branch

## the log of the above I did

Last login: Sun May 14 15:13:28 on console
admin-MacBook-Pro: cd Desktop/
admin-MacBook-Pro:Desktop cd gym/
admin-MacBook-Pro:gym git clone https://github.com/divinecharlotte/bundle-1.git
Cloning into 'bundle-1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
admin-MacBook-Pro:gym $ cd bundle-1/
admin-MacBook-Pro:bundle-1 $ code .
admin-MacBook-Pro:bundle-1 $ git branch

- main
  admin-MacBook-Pro:bundle-1 $ git add .
  admin-MacBook-Pro:bundle-1 $ git status
  On branch main
  Your branch is up to date with 'origin/main'.

Changes to be committed:
(use "git reset HEAD <file>..." to unstage)

    modified:   README.md

admin-MacBook-Pro:bundle-1 $ git add .
admin-MacBook-Pro:bundle-1 $ git push origin main
Everything up-to-date
admin-MacBook-Pro:bundle-1 $ git commit -m "solve bundle1 excercise"
[main ade8b79] solve bundle1 excercise
1 file changed, 13 insertions(+), 1 deletion(-)
rewrite README.md (100%)
admin-MacBook-Pro:bundle-1 $ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 598 bytes | 598.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/divinecharlotte/bundle-1.git
1df25a0..ade8b79 main -> main
admin-MacBook-Pro:bundle-1 $ git checkout -b dev
Switched to a new branch 'dev'
admin-MacBook-Pro:bundle-1 $ git branch

- dev
  main
  admin-MacBook-Pro:bundle-1 $ git checkout test
  error: pathspec 'test' did not match any file(s) known to git
  admin-MacBook-Pro:bundle-1 $ git checkout -b test
  Switched to a new branch 'test'
  admin-MacBook-Pro:bundle-1 $ git branch
  dev
  main
- test
  admin-MacBook-Pro:bundle-1 $ git checkout dev
  Switched to branch 'dev'
  admin-MacBook-Pro:bundle-1 $ git branch
- dev
  main
  test
  admin-MacBook-Pro:bundle-1 $ git branch --delete test
  Deleted branch test (was ade8b79).
  admin-MacBook-Pro:bundle-1 $ git branch
- dev
  main
