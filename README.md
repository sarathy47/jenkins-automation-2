# GitHub-Jenkins-Automation

A simple CI automation project demonstrating the integration of GitHub with Jenkins using a GitHub Webhook.

Whenever code is pushed to the GitHub repository, the webhook automatically triggers a Jenkins build.

## Project Overview

The automation workflow is:

Developer
↓
GitHub Repository
↓
GitHub Webhook
↓
Jenkins
↓
Clone Repository
↓
Execute build.sh
↓
Build Success / Failure

## Technologies Used

- GitHub
- Jenkins
- Git
- Bash / Shell Scripting
- AWS EC2
- Ubuntu Linux
- GitHub Webhooks

## Project Structure

jenkins-automation-2/
│
├── build.sh
└── README.md

## Build Script

The `build.sh` script is executed by Jenkins during the build process.

```bash
#!/bin/bash

echo "================================"
echo "Jenkins GitHub Automation Project"
echo "================================"

echo "Build triggered successfully!"
echo "Repository: jenkins-github-automation"
echo "Build Date: $(date)"
echo "Build completed successfully."

echo "================================"

echo "Jenkins automation test"
echo "Webhook test"
