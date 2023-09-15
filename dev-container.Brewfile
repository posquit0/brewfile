# dev-container.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'


### Container {{{
  # Docker Community Edition for Mac
  cask 'docker'
  # A tool for exploring each layer in a docker image
  brew 'dive'
  # The lazier way to manage everything docker
  brew 'lazydocker'
### }}}


### Kubernetes {{{
  # Kubernetes command-line interface
  brew 'kubernetes-cli'
  # Kubernetes CLI to manage cluters in style
  brew 'k9s'
  
  # The Kubernetes package manager
  tap 'helm/tap'
  brew 'helm'
  # Hosting Helm Charts via GitHub Pages and Releases
  brew 'chart-releaser'
  # CLI tool for linting and testing Helm charts
  brew 'chart-testing'
  # Customization of kubernetes YAML configurations
  brew 'kustomize'
  # Tool for repeatable Kubernetes development
  brew 'skaffold'

  # Plugin manager for kubectl command-line tool
  brew 'krew'
  # Tool that can switch between kubectl contexts easily and create aliases
  brew 'kubectx'
  # Plugin for kubectl OpenID Connect authentication
  tap 'int128/kubelogin'
  brew 'kubelogin'

  # Kubernetes log viewer
  tap 'boz/repo'
  brew 'kail'
  # Multi pod and container log tailing for Kubernetes
  brew 'stern'
  # Bulk port forwarding Kubernetes services for local development
  tap 'txn2/tap'
  brew 'kubefwd'

  # Production Grade K8s Installation, Upgrades, and Management
  brew 'kops'
  # A single-node Kubernetes cluster inside a VM on your laptop
  brew 'minikube'
### }}}
