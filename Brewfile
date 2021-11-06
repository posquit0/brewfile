# Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# http://www.posquit0.com/


cask_args appdir: '/Applications'

# Install and manage GUI macOS applications
tap 'homebrew/cask'
# Alternate versions of Casks
tap 'homebrew/cask-versions'
# Integrates Homebrew formulae with macOS' `launchctl` manager
tap 'homebrew/services'
# A CLI tool upgrading every outdated app installed by Homebrew Cask
# INFO: brew cu
tap 'buo/cask-upgrade'

### System {{{
  ## System Libraries
  # Manage compile and link flags for libraries
  brew 'pkg-config'
  # Text-based UI library
  brew 'ncurses'
  # GNU internationalization (i18n) and localization (l10n) library
  brew 'gettext'
  # Library for command-line editing
  brew 'readline'
  # Core application library for C
  brew 'glib'
  # GNU Transport Layer Security (TLS) Library
  brew 'gnutls'
  # GNU multiple precision arithmetic library
  brew 'gmp'
  # Collection of portable C++ source libraries
  brew 'boost'
  # Vector graphics library with cross-device output support
  brew 'cairo'
  # Framework for layout and rendering of i18n text
  brew 'pango'
  # Image manipulation library
  brew 'jpeg'
  # Library for manipulating PNG images
  brew 'libpng'
  # TIFF library and utilities
  brew 'libtiff'
  # Software library to render fonts
  brew 'freetype'
  # Generic library support script
  # INFO: In order to prevent conflicts with Apple's own libtool we have prepended a "g"
  brew 'libtool'
  # SSL/TLS cryptography library
  brew 'openssl'

  ## Monitoring
  # An interactive process viewer for Unix
  brew 'htop'
  # Display an interface's bandwidth usage
  brew 'iftop'
  # Top-like interface for container metrics
  brew 'ctop'
  # macOS system monitor in your menu bar
  cask 'stats'

  ## Mac OS X
  # Homebrew GUI App for OS X
  cask 'cakebrew'
  # Mac App Store command line interface
  brew 'mas'
  # System Utilities for macOS
  cask 'onyx'
  # Swiss Army Knife for macOS
  brew 'm-cli'

  ## Mac OS X: Quick Look Plugins
  # An Application for Inspecting macOS Installer Packages
  cask 'suspicious-package'
  # View plain text files without a file extension
  # cask 'qlstephen'
  # Preview source code files with syntax highlighting
  cask 'qlcolorcode'
### }}}


### Terminal {{{
  ## Terminal Emulator
  # Terminal Emulator for macOS
  cask 'iterm2'

  ## Terminal Multiplexer
  # Terminal multiplexer with VT100/ANSI terminal emulation
  brew 'screen'
  # A terminal multiplexer, allowing to access multiple separate terminal sessions
  brew 'tmux'
  # Reattach process (e.g., tmux) to background
  brew 'reattach-to-user-namespace'

  ## Shell: Bash
  # Bourne-Again SHell, a UNIX command interpreter
  brew 'bash'
  # Programmable completion for Bash 4.1+
  brew 'bash-completion@2'

  ## Shell: Fish
  # User-friendly command-line shell for UNIX-like operating systems
  # INFO: Need to add `/usr/local/bin/fish` to `/etc/shells`
  brew 'fish'

  ## Shell: Zsh
  # UNIX shell (command interpreter)
  # INFO: Need to add `/usr/local/bin/zsh` to `/etc/shells`
  brew 'zsh'
  # Tips, tricks, and examples for zsh
  brew 'zsh-lovers'
#}}}


### Utility {{{
  # GNU File, Shell, and Text utilities
  brew 'coreutils'
  # Internet file retriever
  brew 'wget'
  # GNU awk utiliy
  brew 'gawk'

  ## Compress/Uncompress
  # 7-Zip (high compression file archiver) implementation
  brew 'p7zip'
  # General-purpose data compression with high compression ratio
  brew 'xz'

  # Display directories as trees
  brew 'tree'
  # Executes a program periodically, showing output fullscreen
  brew 'watch'
  # Simplified and community-driven man pages
  brew 'tldr'
  # Modern replacement for `ls`
  brew 'exa'
  # Clone of cat with syntax highlighting and Git integration
  brew 'bat'
  # Simple, fast and user-friendly alternative to find
  brew 'fd'
  # Yet another cross-platform graphical process/system monitor.
  tap 'clementtsang/bottom'
  brew 'bottom'

  # Boosts your efficiency with hotkeys, keywords, text expansion and more
  cask 'alfred'
  # Organize the menu bar icons
  cask 'bartender'
  # The calendar app you won't be able to live without
  cask 'fantastical'
  # The most awesome keep-awake app
  mas 'Amphetamine', id: 937984704
### }}}


### Web {{{
  ## Web Browser
  cask 'google-chrome'
  cask 'firefox-developer-edition'

  ## Flash Player for Web Browser
  # Adobe Flash Player NPAPI (plugin for Safari and Firefox)
  # cask 'flash-npapi'
  # Adobe Flash Player PPAPI (plugin for Opera and Chromium)
  # cask 'flash-ppapi'
### }}}


### Messaging {{{
  # The best personal email client
  mas 'Spark – Email App by Readdle', id: 1176895641
  # Team communication and collaboration software
  mas 'Slack', id: 803453959
  # Korean standard messaging app
  mas 'KakaoTalk', id: 869223134
  # Messaging app with a focus on speed and security
  cask 'telegram'
### }}}


### Image {{{
  ## Viewer
  # Streamlined and convenient image viewer and browser
  cask 'xee'

  ## Utility
  # Perl lib for reading and writing EXIF metadata
  brew 'exiftool'
### }}}


### Video {{{
  ## Player
  # VLC media player
  cask 'vlc'
  # Home theater/media center software and entertainment hub for digital media
  cask 'kodi'

  ## Recorder
  # An open-source screen recorder built with web technology
  cask 'kap'
### }}}


### Keyboard & Mouse {{{
  # Network KVM Switch(Mouse and Keyboard Sharing)
  cask 'synergy'
  # Customize various input devices on your Mac
  cask 'bettertouchtool'
  # Know your short cuts
  cask 'cheatsheet'
  # A powerful and stable keyboard customizer for macOS
  cask 'karabiner-elements'
### }}}


### Device {{{
  ## Android
  # Android SDK Platform-Tools
  cask 'android-platform-tools'
  # Android File Transfer
  cask 'android-file-transfer'
### }}}


### File System {{{
  ## Cloud
  cask 'google-drive-file-stream'

  ## Recovery
  # Console program to recover files based on their headers and footers
  brew 'foremost'
### }}}


### Cryptography {{{
  # Enhanced version of john, a UNIX password cracker
  brew 'john-jumbo'
  # Suite of barcodes-reading tools
  brew 'zbar'

  ## PGP(Pretty Good Privacy)
  # GNU Pretty Good Privacy (PGP) package
  brew 'gnupg'
  # Pinentry for GPG on Mac
  brew 'pinentry-mac'
  # Custom GPG pinentry program for macOS that allows using Touch ID
  tap 'jorgelbg/tap'
  brew 'pinentry-touchid'

  # Free security app for mobile phones and computers
  # Digital signature manager
  cask 'keybase'
  # A password manager, digital vault, form filler and secure digital wallet
  cask '1password'
### }}}


### Game {{{
  ## Emulator
  cask 'openemu'
### }}}
