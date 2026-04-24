# Copilot Instructions

## Project Overview
This repository is for Spencer Marcu, an American singer-songwriter. It includes a Node.js web application deployed to Azure Web Apps via GitHub Actions.

## Repository Structure
- `README.md` – Project overview
- `.github/workflows/azure-webapps-node.yml` – CI/CD workflow for building and deploying the Node.js app to Azure Web Apps

## Development Guidelines

### Tech Stack
- **Runtime**: Node.js (v20.x or later)
- **Deployment**: Azure Web Apps via GitHub Actions

### Build & Test
This repository does not currently include a `package.json`, so there are no local npm install/build/test commands defined yet.

Use the existing GitHub Actions and Azure Web Apps deployment workflow as the source of truth for build and deployment behavior. If Node project files and npm scripts are added later, update this section and `README.md` with the exact commands to run locally.
### Coding Conventions
- Follow standard Node.js/JavaScript best practices
- Keep dependencies up to date and minimal
- Document any new scripts or workflows clearly

### GitHub Actions
- The deployment workflow targets Azure Web Apps
- Set the `AZURE_WEBAPP_NAME` environment variable to match your app name
- Store deployment credentials in the `AZURE_WEBAPP_PUBLISH_PROFILE` repository secret

## Notes for Copilot
- When making changes, ensure the Azure deployment workflow remains functional
- Prefer small, focused pull requests
- Update `README.md` when adding new features or changing setup instructions
