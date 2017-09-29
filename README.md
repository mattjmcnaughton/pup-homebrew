# pup-homebrew

[sheepdoge](https://github.com/mattjmcnaughton/sheepdoge) pup for managing
dependencies installed through homebrew.

## Dependencies

Currently, `pup-homebrew` presumes you have `homebrew` installed.

## Variables

`pup-homebrew` expects you to define the following variables:
- `pup_homebrew_vars_brew_pkgs` - a list of packages you want installed via
  homebrew.
- `pup_homebrew_vars_brew_deleted_pkgs` a list of packages we want deleted via
  homebrew.
- `pup_homebrew_vars_brew_linked_pkgs` - a list of packages you want installed
  and linked via homebrew.
- `pup_homebrew_vars_brew_cask_pkgs` - a list of packages you want installed
  through brew cask.
- `pup_homebrew_vars_brew_cask_deleted_pkgs` - a list of packages we want
  deleted through brew cask.
