## Código utilizado

```
01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01
$ git init
Initialized empty Git repository in C:/Workspace/DevOps/exe01/.git/

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (master)
$ git add calculadora.py

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (master)
$ git commit -m "subindo calculadora.py para o rep. remoto"
[master (root-commit) 56397cc] subindo calculadora.py para o rep. remoto
 Committer: Elayne Rebeca Machado Silva <01726848@sempreuninassau.com.br>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 64 insertions(+)
 create mode 100644 calculadora.py

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (master)
$ git branch -M main

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (main)
$ git remote add origin https://github.com/ElayneRebeca/RevisaoDevOps08.git

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 902 bytes | 902.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ElayneRebeca/RevisaoDevOps08.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (main)
$ git checkout -b develop
Switched to a new branch 'develop'

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git checkout -b feature/alteracoes-calc
Switched to a new branch 'feature/alteracoes-calc'

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git branch -a
  develop
* feature/alteracoes-calc
  main
  remotes/origin/main

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git push -u origin develop
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'develop' on GitHub by visiting:
remote:      https://github.com/ElayneRebeca/RevisaoDevOps08/pull/new/develop
remote:
To https://github.com/ElayneRebeca/RevisaoDevOps08.git
 * [new branch]      develop -> develop
branch 'develop' set up to track 'origin/develop'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git push -u origin feature/alteracoes-calc
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature/alteracoes-calc' on GitHub by visiting:
remote:      https://github.com/ElayneRebeca/RevisaoDevOps08/pull/new/feature/alteracoes-calc
remote:
To https://github.com/ElayneRebeca/RevisaoDevOps08.git
 * [new branch]      feature/alteracoes-calc -> feature/alteracoes-calc
branch 'feature/alteracoes-calc' set up to track 'origin/feature/alteracoes-calc'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git add .

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git commit -m "alterando o código fazendo commit e push"
[feature/alteracoes-calc 3f1e617] alterando o código fazendo commit e push
 Committer: Elayne Rebeca Machado Silva <01726848@sempreuninassau.com.br>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+), 2 deletions(-)

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes | 352.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ElayneRebeca/RevisaoDevOps08.git
   56397cc..3f1e617  feature/alteracoes-calc -> feature/alteracoes-calc

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git checkout develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git fetch

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git checkout feature/alteracoes-calc
Switched to branch 'feature/alteracoes-calc'
Your branch is up to date with 'origin/feature/alteracoes-calc'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git fetch

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (feature/alteracoes-calc)
$ git checkout develop
Switched to branch 'develop'
Your branch is up to date with 'origin/develop'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git pull origin develop
From https://github.com/ElayneRebeca/RevisaoDevOps08
 * branch            develop    -> FETCH_HEAD
Already up to date.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git merge feature/alteracoes-calc
Updating 56397cc..3f1e617
Fast-forward
 calculadora.py | 3 +--
 1 file changed, 1 insertion(+), 2 deletions(-)

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ElayneRebeca/RevisaoDevOps08.git
   56397cc..3f1e617  develop -> develop

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (develop)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (main)
$ git fetch
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 914 bytes | 9.00 KiB/s, done.
From https://github.com/ElayneRebeca/RevisaoDevOps08
   56397cc..b2dc63e  main       -> origin/main

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (main)
$ git pull origin main
From https://github.com/ElayneRebeca/RevisaoDevOps08
 * branch            main       -> FETCH_HEAD
Updating 56397cc..b2dc63e
Fast-forward
 calculadora.py | 3 +--
 1 file changed, 1 insertion(+), 2 deletions(-)

01726848@UNI001-L004-006 MINGW64 /c/Workspace/DevOps/exe01 (main)
$ git log
commit b2dc63ec821d3ffb8cb067bceb316891176c2ccb (HEAD -> main, origin/main, origin/HEAD)
Merge: 56397cc 3f1e617
Author: Elayne Rebeca <elaynermsilva@gmail.com>
Date:   Wed Apr 15 14:39:14 2026 -0300

    Merge pull request #1 from ElayneRebeca/develop

    alterando o código fazendo commit e push

commit 3f1e61741765a9ef555324129f2dd73ee375ed06 (origin/feature/alteracoes-calc, origin/develop, feature/alteracoes-calc, develop)
Author: Elayne Rebeca Machado Silva <01726848@sempreuninassau.com.br>
Date:   Wed Apr 15 14:34:49 2026 -0300

    alterando o código fazendo commit e push

commit 56397cc24846f6748364fea1dadc906d5409dd43
Author: Elayne Rebeca Machado Silva <01726848@sempreuninassau.com.br>
Date:   Wed Apr 15 14:28:05 2026 -0300

    subindo calculadora.py para o rep. remoto
```