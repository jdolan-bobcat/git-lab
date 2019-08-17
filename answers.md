Answer 1: 2.17.1
Answer 2: user.name=John Dolan
user.email=dolan@ohio.edu
Answer 3: I get a usage command and a list of common git commands and what they each do
Answer 4: I forgot to report what I saw for this one. All three of my files were the red, untracked area.
Answer 5: I see this:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        answers.md
        answers.md.save
 Which showing me what is yet to added. I had gone ahead and added the readme.md before recording this step - the earlier call to status showed me the readme.md as untracked as well.

Answer 6: Now only the answers.md.save is in the red, the answers has been moved to the green.
Answer 7: I see:
[master (root-commit) 2045173] Initial commit
 2 files changed, 22 insertions(+)
 create mode 100644 answers.md
 create mode 100644 readme.md
Answer 8: I see:
commit 20451736b7f7fc96491af10225fac75a224140cb (HEAD -> master)
Author: John Dolan <dolan@ohio.edu>
Date:   Wed Aug 14 13:24:53 2019 -0400


Answer 7: Now that I have opened the answer file to check where I am I 
get this:
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working 
directory)

        modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        answers.md.save

no changes added to commit (use "git add" and/or "git commit -a")

