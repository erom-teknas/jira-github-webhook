# Jira GitHub Automation 🛠️

This repository contains a GitHub Actions workflow for automating tasks triggered by Jira tickets.

## Workflow Description 📋

The workflow is triggered by a manual event (`workflow_dispatch`) and requires the input of the Jira issue key. It runs on an Ubuntu latest runner and performs the following steps:

1. **Display Information**: Prints information about the GitHub event, runner, branch, and repository. 📝
2. **Check out Repository Code**: Checks out the code from the repository using the `actions/checkout` action. 🔍
3. **List Files**: Lists files in the repository directory. 📂
4. **Display Jira Ticket**: Displays the Jira ticket key that triggered the GitHub Action. 🎫

## Usage 🚀

To use this workflow:

1. Fork this repository. 🍴
2. Create or modify your own GitHub Actions workflow file in your repository, and paste the content of `jira-github-automation.yaml` into it. 📄
3. Trigger the workflow manually by selecting "Run workflow" and providing the Jira issue key as an input. 🔑

## Inputs 💼

- **issue_key**: The key of the Jira issue that triggers the GitHub Action. This input is required. 🔖

## Example 🎨

```yaml
on:
  workflow_dispatch:
    inputs:
      issue_key:
        description: 'issue_key'
        required: true
```