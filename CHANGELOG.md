# Changelog
All notable changes to this project will be documented in this file.
This changelog follows the format at [keepachangelog.com](http://keepachangelog.com/).

## [0.2] - 2016-08-10
## Changed
- Replaced tmux build process with a PPA
- Cleaned up YAML formatting (removed superfluous quotations)

## Removed
- Removed steps for cloning oh-my-zsh and Vundle (this is now handled by the dotfiles setup script)

## [0.1.3] - 2016-07-07
## Added
- Added an option to change the system hostname. Useful when injecting this role into someone else's vagrant box.

## [0.1.2] - 2016-06-24
### Changed
- Moved the user creation step up to make sure it exists before creating files underneath the user's home folder.

## [0.1.1] - 2016-06-24
### Added
- Added locale generation.

### Removed
- Removed the Vim plugin installation step. Unfortunately, if there is an error when Vim loads the .vimrc or installs plugins, Vim will display an error message to the console and wait for user input indefinitely, which prevents Ansible from finishing the playbook run.

## [0.1.0] - 2016-06-24
### Added
- Added the first version of the hackbox-user role, based on the original hackbox project.
- Added a README, a LICENCE, and this CHANGELOG.
