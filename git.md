SSH

1) `ssh-keygen -t rsa -b 4096 -C "mahemail"` and `ssh-add -K ~/.ssh/id_rsa`
2) add ssh pub to github/gitcorp website
3) test with `ssh -T git@git.corp.whatever.com`

install gh

`brew install gh`
or https://github.com/cli/cli/blob/trunk/docs/install_linux.md


gh auth login
gh pr view -w
gh pr checkout pr_number
gh pr checks
gh pr diff
gh pr list --author "@me"
gh pr list --search "b60a7888d32ceb6e2eb3323b2a3ce9274d6a2341" --state merged -w
gh pr create --web -d
gh pr status
gh status

git reset HEAD^ ## revert local git commits, keep changes
