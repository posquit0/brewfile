# dev-vcs.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'


### GitHub {{{
  # GitHub command-line tool
  brew 'gh'
  # GitHub notifications on your menu bar. Available on macOS, Windows & Linux
  cask 'gitify'
  # Safari Extension that simplifies the GitHub.com interface and adds useful features.
  mas 'Refined GitHub', id: 1519867270  
### }}}


### VCS: Git {{{
  # Distributed revision control system
  brew 'git'


  ## Git Extension
  # Git extension for versioning large files
  brew 'git-lfs'
  # Modern implementation of the Git-flow branching model
  brew 'git-flow-next'
  # Small git utilities
  brew 'git-extras'


  ## Git Client
  # Text interface for Git repositories
  brew 'tig'
  # A simple terminal UI for git commands
  brew 'lazygit'


  ## Git Utility
  # Prevents you from committing sensitive information to a git repo
  brew 'git-secrets'
  # Audit git repos for secrets
  brew 'gitleaks'
  # Quickly rewrite git repository history (recommended replacement for bfg & git-filter-branch)
  brew 'git-filter-repo'

  # Git credential helper interfacing with pass
  # brew 'pass-git-helper'
  # Secure, cross-platform Git credential storage with authentication to GitHub, Azure Repos, and other popular Git hosting services.
  # tap 'microsoft/git', trusted: true
  # cask 'microsoft/git/git-credential-manager'

  # A framework for managing and maintaining multi-language pre-commit hooks
  brew 'pre-commit'
  # Syntax-highlighting pager for git and diff output
  brew 'git-delta'
  # Review-first terminal diff viewer for agentic coders
  brew 'hunk'
### }}}


### VCS: Mercurial {{{
  # Scalable distributed version control system
  brew 'mercurial'
### }}}


### VCS: SVN {{{
  # Version control system designed to be a better CVS
  brew 'svn'
### }}}
