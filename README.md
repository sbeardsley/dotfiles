# dotfiles

Managed with [chezmoi](https://www.chezmoi.io/).

## Fresh machine setup
```bash
chezmoi init --apply git@github.com:sbeardsley/dotfiles.git
```

## Daily use
```bash
chezmoi add ~/.zshrc        # track a new file
chezmoi edit ~/.zshrc       # edit a tracked file
chezmoi apply               # apply changes to home dir
chezmoi diff                # preview changes before applying
chezmoi cd                  # jump into the repo
```
