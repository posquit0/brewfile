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
  # This plugin helps you to use the AWS Command Line Interface (AWS CLI) to start and end sessions to your managed instances
  cask 'session-manager-plugin'
  # This plugin helps you to use the AWS Command Line Interface (AWS CLI) to start and end sessions to your managed instances
  tap 'disneystreaming/tap'
  # Help manage AWS systems manager with helpers
  brew 'disneystreaming/tap/ssm-helpers'
### }}}


### HashiCorp: Terraform {{{
  tap 'hashicorp/tap'
  # Tool to build, change, and version infrastructure
  # brew 'terraform'
  # A CLI tool to switch between different versions of terraform
  tap 'warrensbox/tap'
  brew 'tfswitch'
  # A Terraform Automation and Collaboration Software credentials helper
  tap 'tonedefdev/terracreds'
  brew 'terracreds'
  # Update version constraints in your Terraform configuration
  tap 'minamijoyo/tfupdate'
  brew 'tfupdate'
  # Interactivity select resource to plan / apply / destroy with target option
  tap 'future-architect/tap'
  brew 'tftarget'
  # Automatic Terraform moved blocks
  tap 'busser/tap'
  brew 'tfautomv'
  # Tool to generate documentation from Terraform modules
  brew 'terraform-docs'
  # Thin wrapper for Terraform e.g. for locking state
  brew 'terragrunt'
  # Terraform linter for detecting errors that can not be detected by `terraform plan`
  brew 'tflint'
  # Security scanner for your Terraform code
  brew 'tfsec'
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
  tap 'argoproj/tap'
  # CLI for ArgoCD
  brew 'argocd'
  # CLI for Argo Workflow
  brew 'argo'
  brew 'kubectl-argo-rollouts'
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
