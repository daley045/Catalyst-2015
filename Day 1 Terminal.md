Last login: Tue Mar  3 20:49:21 on ttys000
Sams-MacBook-Pro-4:~ samdaley$ get status
-bash: get: command not found
Sams-MacBook-Pro-4:~ samdaley$ 
Sams-MacBook-Pro-4:~ samdaley$ cd ~/desktop
Sams-MacBook-Pro-4:desktop samdaley$ show
-bash: show: command not found
Sams-MacBook-Pro-4:desktop samdaley$ pwd
/Users/samdaley/desktop
Sams-MacBook-Pro-4:desktop samdaley$ pwd
/Users/samdaley/desktop
Sams-MacBook-Pro-4:desktop samdaley$ create txt
-bash: create: command not found
Sams-MacBook-Pro-4:desktop samdaley$ txt
-bash: txt: command not found
Sams-MacBook-Pro-4:desktop samdaley$ text edit
-bash: text: command not found
Sams-MacBook-Pro-4:desktop samdaley$ pwd
/Users/samdaley/desktop
Sams-MacBook-Pro-4:desktop samdaley$ touch text.txt
Sams-MacBook-Pro-4:desktop samdaley$ get config --global user.name "Sam Daley"
-bash: get: command not found
Sams-MacBook-Pro-4:desktop samdaley$ get config --global user.name "Sam Daley"
-bash: get: command not found
Sams-MacBook-Pro-4:desktop samdaley$ git config --global user.name "Sam Daley"
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
Sams-MacBook-Pro-4:desktop samdaley$ git clone https://github.com/daley045/Catalyst-2015.git
Cloning into 'Catalyst-2015'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
Checking connectivity... done.
Sams-MacBook-Pro-4:desktop samdaley$ pwd
/Users/samdaley/desktop
Sams-MacBook-Pro-4:desktop samdaley$ ls
Catalyst-2015			Google Drive			som.prize.2015.pdf		text.txt
Daley_Programing Plan.pdf	Time Conflict Form.pdf		spring TA - daley045@umn.pdf
Sams-MacBook-Pro-4:desktop samdaley$ 
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ ls
LICENSE		README.md
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ touch log.md
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ ls
LICENSE		README.md	log.md
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ open log.md
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ pwd
/Users/samdaley/desktop/Catalyst-2015
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote -v
origin	https://github.com/daley045/Catalyst-2015.git (fetch)
origin	https://github.com/daley045/Catalyst-2015.git (push)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ get add --all
-bash: get: command not found
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git commit -m "This is a notation with the uploaded changes!"
-bash: !": event not found
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git commit -m "This is a notation with the uploaded changes"
[master b796825] This is a notation with the uploaded changes
 Committer: Sam Daley <samdaley@nat-10-20-145-77.uofm.wireless.umn.edu>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 32 insertions(+)
 create mode 100644 log.md
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git config --global user.name "Sam Daley"
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git config --global user.emal daley045@umn.edu
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git commit -m
error: switch `m' requires a value
usage: git commit [options] [--] <pathspec>...

    -q, --quiet           suppress summary after successful commit
    -v, --verbose         show diff in commit message template

Commit message options
    -F, --file <file>     read message from file
    --author <author>     override author for commit
    --date <date>         override date for commit
    -m, --message <message>
                          commit message
    -c, --reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --reuse-message <commit>
                          reuse message from specified commit
    --fixup <commit>      use autosquash formatted message to fixup specified commit
    --squash <commit>     use autosquash formatted message to squash specified commit
    --reset-author        the commit is authored by me now (used with -C/-c/--amend)
    -s, --signoff         add Signed-off-by:
    -t, --template <file>
                          use specified template file
    -e, --edit            force edit of commit
    --cleanup <default>   how to strip spaces and #comments from message
    --status              include status in commit message template
    -S, --gpg-sign[=<key id>]
                          GPG sign commit

Commit contents options
    -a, --all             commit all changed files
    -i, --include         add specified files to index for commit
    --interactive         interactively add files
    -p, --patch           interactively add changes
    -o, --only            commit only specified files
    -n, --no-verify       bypass pre-commit hook
    --dry-run             show what would be committed
    --short               show status concisely
    --branch              show branch information
    --porcelain           machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    --amend               amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)

Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Username for 'https://github.com': daley045
Password for 'https://daley045@github.com': 
Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 600 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/daley045/Catalyst-2015.git
   9276e9e..b796825  master -> master
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote -v
origin	https://github.com/daley045/Catalyst-2015.git (fetch)
origin	https://github.com/daley045/Catalyst-2015.git (push)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Everything up-to-date
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ pwd
/Users/samdaley/desktop/Catalyst-2015
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ remote -v
-bash: remote: command not found
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote -v
origin	https://github.com/daley045/Catalyst-2015.git (fetch)
origin	https://github.com/daley045/Catalyst-2015.git (push)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Everything up-to-date
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote -v
origin	https://github.com/daley045/Catalyst-2015.git (fetch)
origin	https://github.com/daley045/Catalyst-2015.git (push)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ 
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Everything up-to-date
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote -v
origin	https://github.com/daley045/Catalyst-2015.git (fetch)
origin	https://github.com/daley045/Catalyst-2015.git (push)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git commit -m "Updated Notes"
[master 63c2702] Updated Notes
 Committer: Sam Daley <samdaley@nat-10-20-145-77.uofm.wireless.umn.edu>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 54 insertions(+), 5 deletions(-)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.23 KiB | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
To https://github.com/daley045/Catalyst-2015.git
   b796825..63c2702  master -> master
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote -v
origin	https://github.com/daley045/Catalyst-2015.git (fetch)
origin	https://github.com/daley045/Catalyst-2015.git (push)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add -all
error: did you mean `--all` (with two dashes ?)
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ get commit -m "Updated Notes to include photos"
-bash: get: command not found
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git commit - m "Updated Notes to Include Photos"
error: pathspec '-' did not match any file(s) known to git.
error: pathspec 'm' did not match any file(s) known to git.
error: pathspec 'Updated Notes to Include Photos' did not match any file(s) known to git.
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Everything up-to-date
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git remote v
error: Unknown subcommand: v
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags|--no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete |<branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git add --all
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git commit -m "Added Photos"
[master f393632] Added Photos
 Committer: Sam Daley <samdaley@nat-10-20-145-77.uofm.wireless.umn.edu>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 8 files changed, 5 insertions(+), 4 deletions(-)
 create mode 100644 .DS_Store
 create mode 100644 Image/.DS_Store
 create mode 100644 Image/MondayMarch9/.DS_Store
 create mode 100644 Image/MondayMarch9/photo 1.JPG
 create mode 100644 Image/MondayMarch9/photo 2.JPG
 create mode 100644 Image/MondayMarch9/photo 3.JPG
 create mode 100644 Image/MondayMarch9/photo 5.JPG
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ git push origin master
Counting objects: 14, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 2.08 MiB | 812.00 KiB/s, done.
Total 12 (delta 3), reused 0 (delta 0)
To https://github.com/daley045/Catalyst-2015.git
   63c2702..f393632  master -> master
Sams-MacBook-Pro-4:Catalyst-2015 samdaley$ 
