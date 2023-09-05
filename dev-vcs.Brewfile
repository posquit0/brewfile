# dev-vcs.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'


### GitHub {{{
  # GitHub command-line tool
  brew 'gh'
  # Safari Extension that simplifies the GitHub.com interface and adds useful features.
  mas 'Refined GitHub', id: 1519867270  
### }}}


### VCS: Git {{{
  # Distributed revision control system
  brew 'git'


  ## Git Extension
  # Git extension for versioning large files
  brew 'git-lfs'
  # Extensions to follow Vincent Driessen's branching model
  brew 'git-flow'
  # Small git utilities
  brew 'git-extras'


  ## Git Client
  # Text interface for Git repositories
  brew 'tig'
  # A simple terminal UI for git commands
  brew 'lazygit'

  # OS X status bar application for GitHub
  # cask 'gitee'
  # The legendary Git GUI client
  # cask 'gitkraken'
  

  ## Git Utility
  # Prevents you from committing sensitive information to a git repo
  brew 'git-secrets'
  # Remove crazy big files, passwords, credentials and other private data
  brew 'bfg'

  # Secure, cross-platform Git credential storage with authentication to GitHub, Azure Repos, and other popular Git hosting services.
  tap 'microsoft/git'
  cask 'git-credential-manager'

  # A framework for managing and maintaining multi-language pre-commit hooks
  brew 'pre-commit'
  # Syntax-highlighting pager for git and diff output
  brew 'git-delta'
### }}}


### VCS: Mercurial {{{
  # Scalable distributed version control system
  brew 'mercurial'
### }}}


### VCS: SVN {{{
  # Version control system designed to be a better CVS
  brew 'svn'
### }}}
