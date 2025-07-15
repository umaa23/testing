# Testing Repository

[![Hello World Workflow](https://github.com/umaa23/testing/actions/workflows/hello-world.yml/badge.svg)](https://github.com/umaa23/testing/actions/workflows/hello-world.yml)
[![Code Quality Checks](https://github.com/umaa23/testing/actions/workflows/code-quality.yml/badge.svg)](https://github.com/umaa23/testing/actions/workflows/code-quality.yml)
[![Update Documentation](https://github.com/umaa23/testing/actions/workflows/documentation.yml/badge.svg)](https://github.com/umaa23/testing/actions/workflows/documentation.yml)

This is a demonstration repository for testing GitHub integration with Claude Code.

## Features
- Automated PR creation
- Git workflow automation
- GitHub CLI integration

## GitHub Actions Examples

This repository contains beginner-friendly GitHub Actions workflows:

### 🌍 Hello World Workflow
- **File**: `.github/workflows/hello-world.yml`
- **Purpose**: Basic introduction to GitHub Actions
- **Triggers**: Push, Pull Request, Manual
- **What it does**: Demonstrates basic workflow syntax, environment variables, and job outputs

### 🔍 Code Quality Checks
- **File**: `.github/workflows/code-quality.yml`
- **Purpose**: Automated code quality validation
- **Triggers**: Push to main/feature branches, Pull Requests
- **What it does**: Checks file structure, content validation, and basic security scans

### 📝 Documentation Updates
- **File**: `.github/workflows/documentation.yml`
- **Purpose**: Automatically update documentation
- **Triggers**: Daily schedule, Manual, Markdown file changes
- **What it does**: Updates README timestamps and generates repository statistics

### 🚀 Deployment Simulation
- **File**: `.github/workflows/deployment.yml`
- **Purpose**: Demonstrates deployment workflows
- **Triggers**: Push to main, Manual
- **What it does**: Simulates deployment to staging and production environments

## Usage
This repository demonstrates how Claude Code can handle the complete GitHub workflow.

## Getting Started with GitHub Actions

1. **View Workflows**: Go to the "Actions" tab in your GitHub repository
2. **Manual Triggers**: Click "Run workflow" for workflows with `workflow_dispatch`
3. **Status Badges**: The badges above show the current status of each workflow
4. **Logs**: Click on any workflow run to see detailed logs and outputs

## Learning Resources

- Replace `umaa23/testing` in the badge URLs with your actual GitHub username and repository name
- Each workflow file contains detailed comments explaining every step
- Start with the Hello World workflow to understand the basics
- The workflows are designed to be safe and educational