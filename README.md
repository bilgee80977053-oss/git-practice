# My Project
- Git PR туршилт

User@216-20 MINGW64 ~
$ https://github.com/bilgee80977053-oss/git-practice.git
bash: https://github.com/bilgee80977053-oss/git-practice.git: No such file or directory

User@216-20 MINGW64 ~
$ cd git-practice
bash: cd: git-practice: No such file or directory

User@216-20 MINGW64 ~
$ git clone https://github.com/bilgee80977053-oss/git-practice.git
Cloning into 'git-practice'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

User@216-20 MINGW64 ~
$ cd git-practice

User@216-20 MINGW64 ~/git-practice (main)
$ echo "# My Project" > README.md

User@216-20 MINGW64 ~/git-practice (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

User@216-20 MINGW64 ~/git-practice (main)
$ git commit -m "Add README.md"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'User@216-20.(none)')

User@216-20 MINGW64 ~/git-practice (main)
$ git config --global user.email "bilgee80977053@gmail.com"

User@216-20 MINGW64 ~/git-practice (main)
$ git config --global user.name "Bilegsaikhan"

User@216-20 MINGW64 ~/git-practice (main)
$ git commit -m "Add README.md"
[main ddac99f] Add README.md
 1 file changed, 1 insertion(+), 1 deletion(-)

User@216-20 MINGW64 ~/git-practice (main)
$ git checkout -b feature-test
Switched to a new branch 'feature-test'

User@216-20 MINGW64 ~/git-practice (feature-test)
$ echo "- Git PR туршилт" >> README.md

User@216-20 MINGW64 ~/git-practice (feature-test)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

User@216-20 MINGW64 ~/git-practice (feature-test)
$ git commit -m "Add Git PR туршилт"
[feature-test fdeb44b] Add Git PR туршилт
 1 file changed, 1 insertion(+)

User@216-20 MINGW64 ~/git-practice (feature-test)
$ git push origin feature-test
info: please complete authentication in your browser...
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 545 bytes | 545.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature-test' on GitHub by visiting:
remote:      https://github.com/bilgee80977053-oss/git-practice/pull/new/feature-test
remote:
To https://github.com/bilgee80977053-oss/git-practice.git
 * [new branch]      feature-test -> feature-test

User@216-20 MINGW64 ~/git-practice (feature-test)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

User@216-20 MINGW64 ~/git-practice (main)
$ git pull origin main
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 918 bytes | 459.00 KiB/s, done.
From https://github.com/bilgee80977053-oss/git-practice
 * branch            main       -> FETCH_HEAD
   15b9306..cb6d0c2  main       -> origin/main
Updating ddac99f..cb6d0c2
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)

User@216-20 MINGW64 ~/git-practice (main)
$ git log --oneline --all --graph
*   cb6d0c2 (HEAD -> main, origin/main, origin/HEAD) Merge pull request #1 from
bilgee80977053-oss/feature-test
|\
| * fdeb44b (origin/feature-test, feature-test) Add Git PR туршилт
| * ddac99f Add README.md
|/
* 15b9306 Initial commit

User@216-20 MINGW64 ~/git-practice (main)
$ git add git-practice.sh
fatal: pathspec 'git-practice.sh' did not match any files

User@216-20 MINGW64 ~/git-practice (main)
$ git commit -m "Add bash script"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@216-20 MINGW64 ~/git-practice (main)
$ git push origin main
Everything up-to-date

User@216-20 MINGW64 ~/git-practice (main)
$ cd ~/git-practice

User@216-20 MINGW64 ~/git-practice (main)
$ git add git-practice.sh
fatal: pathspec 'git-practice.sh' did not match any files

User@216-20 MINGW64 ~/git-practice (main)
$ git commit -m "Add bash script"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@216-20 MINGW64 ~/git-practice (main)
$ git push origin main
Everything up-to-date

User@216-20 MINGW64 ~/git-practice (main)
$ ls
README.md

User@216-20 MINGW64 ~/git-practice (main)
$ ls
README.md

User@216-20 MINGW64 ~/git-practice (main)
$ ls
README.md

User@216-20 MINGW64 ~/git-practice (main)
