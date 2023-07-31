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

```
bash: no job control in this shell
admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "solve bundle exercise 1"
[ft/bundle-2 4605e72] solve bundle exercise 1
 1 file changed, 11 insertions(+)
 create mode 100644 services.html
admin-MacBook-Pro:bundle-1 andela$ git push origin ft/bundle-2
Enumerating objects: 15, done.
admin-MacBook-Pro:bundle-1 andela$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
admin-MacBook-Pro:bundle-1 andela$ git pull
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (11/11), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/divinecharlotte/bundle-1
   3dd4a20..2850839  main       -> origin/main
   1981385..98e7649  dev        -> origin/dev
Updating 3dd4a20..2850839
Fast-forward
 README.md     |  3 +--
 services.html | 11 +++++++++++
 2 files changed, 12 insertions(+), 2 deletions(-)
 create mode 100644 services.html
admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'
admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle2 exercise2"
[ft/service-redesign 1945d2f] bundle2 exercise2
 1 file changed, 1 insertion(+), 1 deletion(-)
admin-MacBook-Pro:bundle-1 andela$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 328 bytes | 328.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/divinecharlotte/bundle-1/pull/new/ft/service-redesign
remote:
To https://github.com/divinecharlotte/bundle-1.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
admin-MacBook-Pro:bundle-1 andela$
```

````
Switched to branch 'ft/service-redesign'
admin-MacBook-Pro:bundle-1 andela$ git diff main
diff --git a/README.md b/README.md
index 341230b..84229e7 100644
--- a/README.md
+++ b/README.md
@@ -77,3 +77,54 @@ admin-MacBook-Pro:bundle-1 $ git branch
 - dev
   main

+```
+bash: no job control in this shell
+admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/bundle-2
+Switched to a new branch 'ft/bundle-2'
+admin-MacBook-Pro:bundle-1 andela$ git add .
+admin-MacBook-Pro:bundle-1 andela$ git commit -m "solve bundle exercise 1"
+[ft/bundle-2 4605e72] solve bundle exercise 1
+ 1 file changed, 11 insertions(+)
+ create mode 100644 services.html
+admin-MacBook-Pro:bundle-1 andela$ git push origin ft/bundle-2
+Enumerating objects: 15, done.
+admin-MacBook-Pro:bundle-1 andela$ git checkout main
+Switched to branch 'main'
+Your branch is up to date with 'origin/main'.
+admin-MacBook-Pro:bundle-1 andela$ git pull
+remote: Enumerating objects: 12, done.
+remote: Counting objects: 100% (11/11), done.
+remote: Compressing objects: 100% (6/6), done.
+remote: Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
+Unpacking objects: 100% (6/6), done.
+From https://github.com/divinecharlotte/bundle-1
+   3dd4a20..2850839  main       -> origin/main
+   1981385..98e7649  dev        -> origin/dev
+Updating 3dd4a20..2850839
+Fast-forward
+ README.md     |  3 +--
+ services.html | 11 +++++++++++
+ 2 files changed, 12 insertions(+), 2 deletions(-)
+ create mode 100644 services.html
+admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/service-redesign
+Switched to a new branch 'ft/service-redesign'
+admin-MacBook-Pro:bundle-1 andela$ git add .
+admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle2 exercise2"
+[ft/service-redesign 1945d2f] bundle2 exercise2
+ 1 file changed, 1 insertion(+), 1 deletion(-)
+admin-MacBook-Pro:bundle-1 andela$ git push origin ft/service-redesign
+Enumerating objects: 5, done.
+Counting objects: 100% (5/5), done.
+Delta compression using up to 4 threads
+Compressing objects: 100% (3/3), done.
+Writing objects: 100% (3/3), 328 bytes | 328.00 KiB/s, done.
+Total 3 (delta 2), reused 0 (delta 0)
+remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
+remote:
+remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
+remote:      https://github.com/divinecharlotte/bundle-1/pull/new/ft/service-redesign
+remote:
+To https://github.com/divinecharlotte/bundle-1.git
+ * [new branch]      ft/service-redesign -> ft/service-redesign
+admin-MacBook-Pro:bundle-1 andela$
+```
diff --git a/services.html b/services.html
index c097217..a44ec5b 100644
--- a/services.html
+++ b/services.html
@@ -6,6 +6,6 @@
     <title>service</title>
 </head>
 <body>
-    <p>service content</p>
+    <p>content</p>
 </body>
 </html>
\ No newline at end of file
(END)



bash: no job control in this shell
admin-MacBook-Pro:bundle-1 andela$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
admin-MacBook-Pro:bundle-1 andela$ git add .
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
   d7fc279..b231b48  ft/service-redesign -> ft/service-redesign
admin-MacBook-Pro:bundle-1 andela$
````

## BUNDLE3-LOG

```
bash: no job control in this shell
admin-MacBook-Pro:bundle-1 andela$ git log --oneline
admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
admin-MacBook-Pro:bundle-1 andela$ git add .
admin-MacBook-Pro:bundle-1 andela$ git commit -m "bundle 3 exercercise 1"
[ft/team-page 13ba4dd] bundle 3 exercercise 1
1 file changed, 11 insertions(+)
admin-MacBook-Pro:bundle-1 andela$ git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 407 bytes | 407.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote: https://github.com/divinecharlotte/bundle-1/pull/new/ft/team-page
remote:
To https://github.com/divinecharlotte/bundle-1.git

- [new branch] ft/team-page -> ft/team-page
  admin-MacBook-Pro:bundle-1 andela$ git checkout main
  Switched to branch 'main'
  Your branch is up to date with 'origin/main'.
  admin-MacBook-Pro:bundle-1 andela$ git checkout -b ft/contact-page
  Switched to a new branch 'ft/contact-page'
  admin-MacBook-Pro:bundle-1 andela$ git checkout ft/team-page
  Switched to branch 'ft/team-page'


 ** admin-MacBook-Pro:bundle-1 andela$ git log --oneline


13ba4dd (HEAD -> ft/team-page, origin/ft/team-page) bundle 3 exercercise 1
44248fc (origin/ft/service-redesign, ft/service-redesign) solve conflicts locally
b231b48 solve conflicts locally
e0273ea (origin/main, origin/HEAD, main, ft/contact-page) bundle2 exercise2 part2
d7fc279 bundle2 exercise2
1945d2f bundle2 exercise2
2850839 Merge pull request #2 from divinecharlotte/ft/bundle-2
4605e72 (origin/ft/bundle-2, ft/bundle-2) solve bundle exercise 1
f946f8c Merge pull request #1 from divinecharlotte/dev
98e7649 (origin/dev) Merge branch 'main' into dev
1981385 (dev) do bundle1 exercise2
3dd4a20 do bundle1 exercise2
25d86c7 update the log of all I did
f632257 update the log of all I did
ade8b79 solve bundle1 excercise
1df25a0 Initial commit

```

```

```
