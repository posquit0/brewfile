# dev-terminal.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'

### Terminal Emulator {{{
  ## Terminal Emulator
  # Rust-based terminal
  cask 'warp' if OS.mac?

  # Terminal Emulator for macOS
  cask 'iterm2' if OS.mac?
  # A GPU-accelerated cross-platform terminal emulator and multiplexer
  cask 'wezterm'
### }}}


### Terminal Multiplexer {{{
  # A terminal workspace with batteries included
  brew 'zellij'

  # Terminal multiplexer with VT100/ANSI terminal emulation
  brew 'screen'
  # A terminal multiplexer, allowing to access multiple separate terminal sessions
  brew 'tmux'
  # Reattach process (e.g., tmux) to background
  brew 'reattach-to-user-namespace'
### }}}


### Shell: Bash {{{
  # Bourne-Again SHell, a UNIX command interpreter
  brew 'bash'
  # Programmable completion for Bash 4.1+
  brew 'bash-completion@2'
### }}}


### Shell: Fish {{{
  # User-friendly command-line shell for UNIX-like operating systems
  # INFO: Need to add `/usr/local/bin/fish` to `/etc/shells`
  brew 'fish'
### }}}


### Shell: Zsh {{{
  # UNIX shell (command interpreter)
  # INFO: Need to add `/usr/local/bin/zsh` to `/etc/shells`
  brew 'zsh'
  # Tips, tricks, and examples for zsh
  brew 'zsh-lovers'
### }}}


### Utility {{{
  # GNU File, Shell, and Text utilities
  brew 'coreutils'
  # Internet file retriever
  brew 'wget'


  ## Filesystem
  # Modern replacement for `ls`
  brew 'exa'
  # Display directories as trees
  brew 'tree'
  # A new way to see and navigate directory trees
  brew 'broot'
  # A command-line fuzzy finder
  brew 'fzf'
  # A smarter `cd` command
  brew 'zoxide'
  # Clone of cat with syntax highlighting and Git integration
  brew 'bat'

  # Simple, fast and user-friendly alternative to find
  brew 'fd'
  # An extremely fast alternative to grep that respects your gitignore
  brew 'ripgrep'
  # GNU awk utiliy
  brew 'gawk'

  # Disk Usage/Free Utility - a better 'df' alternative
  brew 'duf'
  # A more intuitive version of du in rust
  brew 'dust'


  ## Compress
  # 7-Zip (high compression file archiver) implementation
  brew 'p7zip'
  # General-purpose data compression with high compression ratio
  brew 'xz'
  

  ## Process
  # Executes a program periodically, showing output fullscreen
  brew 'watch'
  # A modern watch command. Time machine and pager etc
  brew 'viddy'

  # A modern replacement for ps written in Rust
  brew 'procs'


  ## Monitoring
  # Yet another cross-platform graphical process/system monitor.
  brew 'bottom'
  # An interactive process viewer for Unix
  brew 'htop'
  # Display an interface's bandwidth usage
  brew 'iftop'
  # Top-like interface for container metrics
  brew 'ctop'
  # Glances an Eye on your system
  brew 'glances'


  ## MISC
  # Simplified and community-driven man pages
  brew 'tldr'
  # Create and view interactive cheatsheets on the command-line
  brew 'cheat'
  # Record and share your terminal sessions, the simple way
  brew 'asciinema'
### }}}
