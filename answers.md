1. git version 2.17.1
2. user.name=ayang
   user.email=ay764920@ohio.edu
3. git usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
4. On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md
5. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

6. On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   answers.md 
(Before I added "answers.md" to the staging area I have accidentally skipped this, and did 'git commit -m "Initial commit" ', and after doing so I have just realized I forgot to do step 6, which I did just now)
7. On branch master
nothing to commit, working tree clean
ayang@odd39:~/cs2400/git-lab$ 
8. commit 2047559970eb679e05de8b3ffae552cd2e098869 (HEAD -> master)
Author: ayang <ay764920@ohio.edu>
Date:   Fri Jan 21 14:57:25 2022 -0500

    Initial commit

commit ffd162aef104ddd192c3426e16201e57806be4d5
Author: ayang <ay764920@ohio.edu>
Date:   Fri Jan 21 14:51:23 2022 -0500
9. On branch main
Your branch is up to date with 'origin/main'.
10. No
11. To https://github.com/ayang55/git-lab1.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/ayang55/git-lab1.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
12. Yes lets go
13. .  ..  .git  .gitignore  README.md



