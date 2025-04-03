# Git Markdown

[Git Cheat Sheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)

[So you know git?](https://www.youtube.com/watch?v=aolI_Rz0ZqY)


## Alias list

The following code will set up short aliases for git commands:

    git config --global alias.co checkout
    git config --global alias.br branch
    git config --global alias.ci commit
    git config --global alias.st status
    git config --global alias.ad "add --all"
	git config --global alias.adgo  "log --all --decorate --graph --oneline"

To edit aliases, open file `~/.gitconfig`

## Undo changes

To undo last change and keep / reset changes:

    git reset --soft HEAD~1

    git reset --hard HEAD~1

## Misc

    git maintenance start

    git range-diff ref1 ref2
