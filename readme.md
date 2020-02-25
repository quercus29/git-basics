# Git Basics February 24, 2020 Safari Live/Daniel Chen

## Local
=======
- `config`: make and view various configuration settings
- `init`: make current folder a git directory
- `status`: see the git status of the current directory
- `add`: put files into the staging area
- `commit`: commit the files from staging area
- `git commit -m <MESSAGE>`: add MESSAGE describing the commit (?? the purpose, etc)
- `index/staging area`: an intermediate area to collect materials to be committed, prior to committing
- `diff`: look at differences between 2 commit states, staging state by using --stage, or specific files, but adding filename as arg
- `log`: get list of all commits with messages
- `checkout`: changes what HEAD points to (i.e. which commit)

## Remotes

- `remote`: anywhere that you didnt `init` or `clone`
	- `remote add origin <url>`: adds the url as a remote named origin
	- `remote -v`: shows remote
- `push`: send code to remote
- `pull`: get code from remote (= fetch + merge)

