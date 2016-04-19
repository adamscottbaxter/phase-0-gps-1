# phase-0-gps-1

  661  git clone git@github.com:adamscottbaxter/phase-0-gps-1.git
  * Makes a copy of the entire repo on the local computer
  662  ls
  * Lists the contents of the directory
  663  cd phase-0-gps-1/
  * Change directory
  664  ls
  665  touch awesome_page.md
  * Creates a markdown file in the working directory
  666  ls
  667  git status
  * Displays the status of the files of the branch you are working in.
  668  ls
  669  add awesome_page.md 
  * mistake
  670  git add awesome_page.md 
  * Stages the listed file to be committed
  671  git status
  672  git commit -m "makes awesome_page.md"
  * Creates a snapshot / checkpoint of the files in the branch and includes a change message.
  673  git status
  674  git push origin master
  * Takes all local changes and pushes the changes to the remote repo on github.
  675  git status
  676  git checkout -b "add-command-long"
  677  git branch
  678  git checkout -b "add-command-log"
  679  git branch
  680  git branch -d add-command-log
  681  git checkout master
  682  git branch -d add-command-long
  683  git branch
  684  git branch -d add-command-log
  685  git branch
  686  git checkout -b "add-command-log"
  687  git branch
  688  ls
  689  subl readme.md
  690  history
  691  history 20
  692  history 50
  693  history 50 >> readme.md
