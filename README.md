# Project 7: CI Validation for Terraform

![Terraform CI](https://github.com/Mahesh-Polisetti/project-7-terraform-ci/actions/workflows/terraform.yml/badge.svg)

## Goal
Automate Infrastructure as Code (IaC) checks using GitHub Actions.

## Tasks
- Run Terraform fmt checks.
- Initialize Terraform.
- Validate Terraform configuration automatically on push and pull requests.

## Tools Used
- Terraform
- Git
- GitHub
- GitHub Actions

## Pipeline Status
Terraform CI validation workflow executes automatically on every push and pull request to the main branch.

## Infrastructure Changes with Branching Policy

- Follow Git feature branching strategy.
- Create infrastructure changes in a separate feature branch.
- Commit and push changes to GitHub.
- Submit changes through a Pull Request.
- Review and merge approved changes into main.
