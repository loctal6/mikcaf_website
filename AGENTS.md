# MikCafe Website - Development Instructions

## Project Context

This repository contains the official MikCafe website.

- Production website: [https://mikcaf.com/](https://mikcaf.com/)
- GitHub repository: [https://github.com/loctal6/mikcaf_website](https://github.com/loctal6/mikcaf_website)
- Production branch: main
- Hosting: Hostinger
- Deployment: GitHub Actions using the existing FTP deployment workflow.

## Development Rules

1. Always work within this repository.
2. Inspect the existing project structure and code before making changes.
3. Preserve the existing design language, branding, responsive behaviour, and functionality unless explicitly instructed otherwise.
4. Do not introduce unnecessary frameworks, dependencies, or build systems.
5. Keep code clean, maintainable, and optimized for performance.
6. Test changes wherever practical before considering a task complete.
7. Never modify FTP credentials, GitHub secrets, or the existing deployment workflow unless explicitly instructed.
8. Never delete existing assets or functionality without explaining why and obtaining approval.

## Git Workflow

1. Work on the main branch unless explicitly instructed otherwise.
2. Before committing, inspect git status and the complete diff.
3. Use descriptive commit messages.
4. Never force-push, rewrite Git history, or discard user changes.
5. Do not commit secrets, credentials, or temporary files.
6. Only commit and push when explicitly instructed by the user.
7. After pushing, verify that the push succeeded.

## Deployment

The existing GitHub Actions workflow automatically deploys changes pushed to main.
Do not manually upload files through FTP.
Do not recreate or replace the existing deployment pipeline.
After a push, report the GitHub Actions deployment status if it can be verified.

## Communication

Before significant changes, explain the proposed approach.
After completing a task, summarize:

- Files changed
- Functionality added or modified
- Tests performed
- Git commit and push status
- Deployment status, when available
