



1: git version 2.39.2 (Apple Git-143)

2:  credential.helper=osxkeychain
    init.defaultbranch=main
    user.name=Jake Belmont
    user.email=jakebelmont7@gmail.com

3:git-commit - Record changes to the repository

SYNOPSIS
       git commit [-a | --interactive | --patch] [-s] [-v] [-u<mode>] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>)]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

DESCRIPTION
       Create a new commit containing the current contents of the index and the given log message describing the
       changes. The new commit is a direct child of HEAD, usually the tip of the current branch, and the branch is
       updated to point to it (unless no branch is associated with the working tree, in which case HEAD is "detached"
       as described in git-checkout(1)).

The help command brings up a full description of what ever command was selected in the command. It also has tips on the ways the command is used and much more




4: On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md
	answers.md

5: On branch main

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
	        new file:   README.md

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
	        answers.md

6:On branch main

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
	        new file:   README.md
	        new file:   answers.md

7: 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 answers.md

 8: On branch main
    nothing to commit, working tree clean
    jakebelmont@Jakes-MacBook-Air-5 git-lab % git log
    commit ef0113ee6785fff7e10ccae516a9f059cefdf15b (HEAD -> main)
    Author: Jake Belmont <jakebelmont7@gmail.com>
    Date:   Tue Jan 21 10:46:55 2025 -0500

    Initial commit

9: On branch main
    Your branch is up to date with 'origin/main'.

    Changes not staged for commit:
        (use "git add <file>..." to update what will be committed)
            (use "git restore <file>..." to discard changes in working directory)
	        modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")

10: On branch main
    Your branch is up to date with 'origin/main'.

        Changes not staged for commit:
         (use "git add <file>..." to update what will be committed)
            (use "git restore <file>..." to discard changes in working directory)
	            modified:   answers.md
11:jakebelmont@Jakes-MacBook-Air-5 git-lab % git push
    To https://github.com/JakeBelmont03/git-lab.git
    ! [rejected]        main -> main (fetch first)
    error: failed to push some refs to 'https://github.com/JakeBelmont03/git-lab.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12:(Yes online changes were updated to the local file)
CS 2400, section 110


name :jake belmont
gitHub user: jakebelmont03


Email: jb010123@ohio.edu 

Location: answers saved in answers.md

13:
jakebelmont@Jakes-MacBook-Air-5 git-lab-2 % ls -a
.		..		.git		.gitignore	README.md



