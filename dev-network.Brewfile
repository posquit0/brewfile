# dev-network.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'

### Analysis {{{
  # Terminal UI for tshark, inspired by Wireshark
  brew 'termshark'
  # The command-line utilities of Wireshark 
  brew 'wireshark'
  # The world’s foremost and widely-used network protocol analyzer (GUI version of Wireshark)
  cask 'wireshark-app'
  # If your list of available capture interfaces is empty
  # cask 'wireshark-chmodbpf'
  # Port scanning utility for large networks
  brew 'nmap'
  # Command-line DNS Client for Humans. Written in Golang
  brew 'doggo'

  # Analyze Monitor Optimize Wi-Fi
  mas 'WiFi Explorer: Scanner', id: 494803304  
### }}}


### Proxy & VPN {{{
  ## Proxy & VPN
  # Free software for OpenVPN on OS X
  cask 'tunnelblick'
  # For an instant, secure URL to your localhost server through any NAT or firewall
  cask 'ngrok'
### }}}


### Remote Access {{{
  # Fast and secure remote desktop
  mas 'Jump Desktop (RDP, VNC, Fluid)', id: 524141863
  # Remote desktop app
  cask 'jump-desktop-connect'
### }}}


### Utility {{{
  # GNU utilities for networking
  brew 'inetutils'
  # MAC spoofing GUI for macOS
  cask 'linkliar' if OS.mac?
### }}}
