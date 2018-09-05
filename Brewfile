# Brewfile
#
# Maintained by Claud D. Park <posquit0.bj@gmail.com>
# http://www.posquit0.com/


cask_args appdir: '/Applications'

### System {{{
  ## System Libraries
  # Manage compile and link flags for libraries
  brew 'pkg-config'
  # Text-based UI library
  brew 'ncurses'

  ## Mac OS X
  brew 'm-cli'

  ## Monitoring
  brew 'htop', args: ['with-ncurses']
  # Display an interface's bandwidth usage
  brew 'iftop'
  # Top-like interface for container metrics
  brew 'ctop'
### }}}

### Web Browser {{{
  cask 'google-chrome'
  cask 'firefox-developer-edition'

### }}}

### Network {{{
  ## Analysis
  cask 'wireshark'
### }}}

### Programming Language {{{
  ## Node.js
  brew 'node'
### }}}

### Code Editor & IDE {{{
  ## Editors
  # Vim
  brew 'neovim'
  # Microsoft Visual Studio Code
  cask 'visual-studio-code'

  ## IDE
  # JetBrain
  cask 'webstorm'
  cask 'intellij-idea'
### }}}
