How to clone and use Git Repo

1. clone the repo: git clone https://github.com/mohamk-zwift/SamaTest.git
1. make whatever file changes you
1. Flow of git:
    1. `git status`: shows the files changed
    1. `git add .` OR `git add <file-name>`: gets files read for staging
        1. `git add test-read.md`: this will add "test-read.md" for staging
    1. `git commit -m <type-message-here>`: this will assign a commit message
    1. `git push -u origin main`: pushes repo to remote server
1. Other command
    1. `git pull`: this will pull the most recent changes from the remote repo
    1. `git log`: shows history of repo, basically showing the list of commits, messages associated with commits, and time
        1. `git log --oneline`: simpler view of history

