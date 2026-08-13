# dotfiles

Personal configuration files for macOS and Linux.

## Contents

- `zsh/` – shell aliases and prompt
- `git/` – global gitignore and config
- `vim/` – lightweight editor setup

## Install

Symlink files manually or use `stow`:

```bash
stow zsh git vim
```

## Notes

- Keep secrets out of this repo (use `.env` or keychain).
- Test changes in a fresh shell before committing.
