# secret.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'


### Cryptography {{{
  # GNU Transport Layer Security (TLS) Library
  brew 'gnutls'

  # SSL/TLS cryptography library
  brew 'openssl'
  # Enhanced version of john, a UNIX password cracker
  brew 'john-jumbo'
  # Suite of barcodes-reading tools
  brew 'zbar'
### }}}


### PGP (Pretty Good Privacy) {{{
  # GNU Pretty Good Privacy (PGP) package
  brew 'gnupg'
  # Manage your GnuPG keys with ease!
  brew 'gpg-tui'
  # Pinentry for GPG on Mac
  brew 'pinentry-mac' if OS.mac?
  # Custom GPG pinentry program for macOS that allows using Touch ID
  tap 'jorgelbg/tap'
  brew 'pinentry-touchid' if OS.mac?
### }}}


## Secrets {{{
  # A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability
  brew 'age'
  # The slightly more awesome standard unix password manager for teams
  brew 'gopass'
  # Editor of encrypted files
  brew 'sops'

  # A password manager, digital vault, form filler and secure digital wallet
  cask '1password'
  # Command-line helper for the 1Password password manager
  cask '1password-cli'
  # Safari Extension for 1Password
  mas '1Password for Safari', id: 1569813296
  # A lightweight app to register your device to Okta
  mas 'Okta Verify', id: 490179405
  # Application for configuring any YubiKey
  cask 'yubico-yubikey-manager'

  # Free security app for mobile phones and computers
  # Digital signature manager
  cask 'keybase'
### }}}
