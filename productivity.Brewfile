# productivity.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'

# Alternate versions of Casks
tap 'homebrew/cask-versions'


### Launcher {{{
  # Boosts your efficiency with hotkeys, keywords, text expansion and more
  # cask 'alfred'
  # Control your tools with a few keystrokes
  cask 'raycast' if OS.mac?
### }}}


### Menu Bar {{{
  # A powerful menu bar browser
  mas 'MenubarX', id: 1575588022
  # Organize the menu bar icons
  cask 'bartender' if OS.mac?

  # The most awesome keep-awake app
  mas 'Amphetamine', id: 937984704
  # macOS system monitor in your menu bar
  cask 'stats' if OS.mac?
### }}}


### Time Management {{{
  # The calendar app you won't be able to live without
  # cask 'fantastical'
  # Calendar software focusing on flexibility and reliability
  # cask 'busycal'
  # Calendar for professionals and teams
  cask 'notion-calendar'
### }}}


### Keyboard & Mouse & Trackpad {{{
  # Customize various input devices on your Mac
  cask 'bettertouchtool' if OS.mac?
  # Know your short cuts
  cask 'cheatsheet' if OS.mac?

  # A powerful and stable keyboard customizer for macOS
  cask 'karabiner-elements' if OS.mac?
  # Network KVM Switch(Mouse and Keyboard Sharing)
  # cask 'synergy'
### }}}
