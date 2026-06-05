# devops.Brewfile
#
# Maintained by Byungjin Park <posquit0.bj@gmail.com>
# https://www.posquit0.com/


cask_args appdir: '/Applications'

### AWS {{{
  # Universal Command Line Interface for AWS
  brew 'awscli'
  # A vault for securely storing and accessing AWS credentials in development environments
  cask 'aws-vault'
  # A terminal-based AWS resource viewer and manager
  tap 'huseyinbabal/tap', trusted: true
  brew 'huseyinbabal/tap/taws'
  # k9s-inspired TUI for AWS resource management with vim-style navigation
  tap 'clawscli/tap', trusted: true
  brew 'clawscli/tap/claws'
  # This plugin helps you to use the AWS Command Line Interface (AWS CLI) to start and end sessions to your managed instances
  cask 'session-manager-plugin'
  # This plugin helps you to use the AWS Command Line Interface (AWS CLI) to start and end sessions to your managed instances
  tap 'disneystreaming/tap', trusted: true
  # Help manage AWS systems manager with helpers
  brew 'disneystreaming/tap/ssm-helpers'
### }}}


### HashiCorp: Terraform {{{
  tap 'hashicorp/tap', trusted: true
  # Tool to build, change, and version infrastructure
  # brew 'terraform'
  # A CLI tool to switch between different versions of terraform
  tap 'warrensbox/tap', trusted: true
  brew 'tfswitch'
  # A Terraform Automation and Collaboration Software credentials helper
  tap 'tonedefdev/terracreds', trusted: true
  brew 'terracreds'
  # Update version constraints in your Terraform configuration
  tap 'minamijoyo/tfupdate', trusted: true
  brew 'tfupdate'
  # Interactivity select resource to plan / apply / destroy with target option
  tap 'future-architect/tap', trusted: true
  brew 'tftarget'
  # Automatic Terraform moved blocks
  tap 'busser/tap', trusted: true
  brew 'tfautomv'
  # Tool to generate documentation from Terraform modules
  brew 'terraform-docs'
  # A schema inspector for Terraform providers
  tap 'minamijoyo/tfschema', trusted: true
  brew 'tfschema'
  # Display your Terraform module call stack in your terminal
  tap 'busser/tap', trusted: true
  brew 'tftree'
  # Thin wrapper for Terraform e.g. for locking state
  brew 'terragrunt'
  # Terraform linter for detecting errors that can not be detected by `terraform plan`
  brew 'tflint'
  # Security scanner for your Terraform code
  brew 'tfsec'
  # Terraform textual UI
  tap 'idoavrah/homebrew', trusted: true
  brew 'tftui'
  # Drive terraform at terminal velocity
  tap 'leg100/tap', trusted: true
  brew 'pug'
  # Cost estimates for Terraform
  brew 'infracost'
### }}}


### HashiCorp: Packer {{{
  # Tool for creating identical machine images for multiple platforms
  brew 'packer'
### }}}


### HashiCorp: Vagrant {{{
  # Tool for building and managing virtual machine environments
  cask 'hashicorp/tap/hashicorp-vagrant'
  # Manage your vagrant machines in one place
  # cask 'vagrant-manager'
### }}}


### HashiCorp: Boundary {{{
  # Identity-based access management for dynamic infrastructure.
  brew 'hashicorp/tap/boundary'
  cask 'hashicorp/tap/hashicorp-boundary-desktop'
### }}}


### HashiCorp: Consul {{{
  # A distributed, highly available, and data center aware solution to connect and configure applications across dynamic, distributed infrastructure.
  brew 'hashicorp/tap/consul'
  # First-class support for Consul Service Mesh on Kubernetes 
  brew 'hashicorp/tap/consul-k8s'
### }}}


### HashiCorp: HCP {{{
  # CLI for HCP (HashiCorp Cloud Platform)
  brew 'hashicorp/tap/hcp'
### }}}


### Ansible {{{
  # Automate deployment, configuration, and upgrading
  brew 'ansible'
  # Best practices checker for Ansible
  brew 'ansible-lint'
  # Molecule aids in the development and testing of Ansible roles
  # INFO: Install using pip
  # brew 'molecule'
### }}}


### Kubernetes {{{
  tap 'argoproj/tap', trusted: true
  # CLI for ArgoCD
  brew 'argocd'
  # CLI for Argo Workflow
  brew 'argo'
  brew 'kubectl-argo-rollouts'

  # Istio configuration command-line utility
  brew 'istioctl'
### }}}


### CI / CD {{{
  ## GitHub Actions
  # Run your GitHub Actions locally
  brew 'act'
  # Static checker for GitHub Actions workflow files
  brew 'actionlint'

  # Enables you to reproduce the CircleCI environment locally
  # brew 'circleci'
  # Command line tool for Drone CI
  # tap 'drone/drone'
  # brew 'drone'
### }}}


### MISC {{{
  # Artificial Intelligence Infrastructure-as-Code Generator
  tap 'gofireflyio/aiac', trusted: true
  brew 'aiac'

  # Develop and deploy code with zero configuration
  brew 'railway'
### }}}
