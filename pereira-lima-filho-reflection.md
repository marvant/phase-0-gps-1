__What Git concepts were you struggling with prior to the GPS session?__
  We had problems merging conflicts, but today thinking about this and looking into the history command, I realized what we did wrong. I think after the manual merge, we performed a wrong commnand "git merge origin" and the exercise did not ask for this.

    672  git add awesome_page.md
    673  git commit -m "add some markdown"
    674  git push origin release_4
    675  git branch
    676  git checkout -b small-conflict
    677  subl .
    678  git add awesome_page.md
    679  git commit -m "add bold markdown"
    680  git co master
    681  subl awesome_page.md
    682  git add awesome_page.md
    683  git commit -m "add test"
    684  git merge small-conflict
    685  git status
    686  subl .
    687  git add awesome_page.md
    688  git commit -m "the conflict was resolved"
    689  git status
    **690  git merge origin** <----------------
    691  git branch
    692  git status
    693  git push origin master


__What concepts were clarified during the GPS?__
  How to choose who will driver or navigate and fetch command.

__What questions did you ask your pair and the guide?__
  Some times I asked why we were executing some commands.

__What still confuses you about Git?__
  I still confused about this topic:

    3. Merge the small-conflict branch to the master. Discuss what you are doing when you merge two branches together like this.

  Following the git workflow, I think we had to perform inside the small-conflic branch "git merge master", and what we did were from master branch, "git merge small-conflict".
  Is this correct ?

__How was your first experience of pairing in a GPS?__
  In the start was difficult because I was a little bit nervous, but after 15/20 minutes I started to have fun!!.