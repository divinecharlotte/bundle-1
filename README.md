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

### CHERRYPICKING:

```
admin-MacBook-Pro:bundle-1 andela$ git cherry-pick e0273ea
On branch ft/contact-page
You are currently cherry-picking commit e0273ea.

nothing to commit, working tree clean
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git reset'
admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle 3 exercercise 1 cherry commang"
[ft/contact-page c871852] bundle 3 exercercise 1 cherry commang
 Date: Fri Jul 28 15:22:22 2023 +0200
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html
admin-MacBook-Pro:bundle-1 andela$ git push origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 442 bytes | 442.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/divinecharlotte/bundle-1/pull/new/ft/contact-page
remote:
To https://github.com/divinecharlotte/bundle-1.git
 * [new branch]      ft/contact-page -> ft/contact-page
admin-MacBook-Pro:bundle-1 andela$
```

admin-MacBook-Pro:bundle-1 andela$ git commit -m "solve conflicts locally"
[ft/service-redesign b231b48] solve conflicts locally
admin-MacBook-Pro:bundle-1 andela$ git push ft/service-redesign
fatal: 'ft/service-redesign' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
admin-MacBook-Pro:bundle-1 andela$ git push origin ft/service-rede
sign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 349 bytes | 349.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/divinecharlotte/bundle-1.git
d7fc279..b231b48 ft/service-redesign -> ft/service-redesign
admin-MacBook-Pro:bundle-1 andela$

```

```

### BUNDLE3EXERCESISE2

```

admin-MacBook-Pro:bundle-1 andela$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/faq-page
Switched to branch 'ft/faq-page'
admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
admin-MacBook-Pro:bundle-1 andela$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle 3 exercesise2"
[main 46f1119] bundle 3 exercesise2
 1 file changed, 11 insertions(+)
admin-MacBook-Pro:bundle-1 andela$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
admin-MacBook-Pro:bundle-1 andela$ git rebase main
First, rewinding head to replay your work on top of it...
Applying: bundle 3 exercercise 1 cherry commang
Applying: bundle 3 exercercise 1 cherry commanD
Applying: bundle 3 exercercise 1 faq page
Applying: Revert "bundle2 exercise2 part2"
Applying: solve conflicts
Applying: solve conflicts
Applying: Revert "bundle2 exercise2 part2"
Applying: add team page
Using index info to reconstruct a base tree...
M       team.html
Falling back to patching base and 3-way merge...
Auto-merging team.html
CONFLICT (content): Merge conflict in team.html
error: Failed to merge in the changes.
Patch failed at 0008 add team page
hint: Use 'git am --show-current-patch' to see the failed patch

Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".

admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle 3 exercesise2"
rebase in progress; onto 46f1119
You are currently rebasing branch 'ft/home-page-redesign' on '46f1119'.

nothing to commit, working tree clean
admin-MacBook-Pro:bundle-1 andela$ git rebase --continue
Applying: add team page
To abort and get back to the state before "git rebase", run "git rebase --abort".

admin-MacBook-Pro:bundle-1 andela$ git rebase --skip
admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle 3 exercesise2"
On branch ft/home-page-redesign
nothing to commit, working tree clean
admin-MacBook-Pro:bundle-1 andela$ git push origin ft/home-page-redesign
Enumerating objects: 26, done.
Counting objects: 100% (26/26), done.
Delta compression using up to 4 threads
Compressing objects: 100% (22/22), done.
Writing objects: 100% (22/22), 2.89 KiB | 985.00 KiB/s, done.
Total 22 (delta 15), reused 0 (delta 0)
remote: Resolving deltas: 100% (15/15), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/divinecharlotte/bundle-1/pull/new/ft/home-page-redesign
remote:
To https://github.com/divinecharlotte/bundle-1.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
admin-MacBook-Pro:bundle-1 andela$
```
