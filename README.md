# CICD-using-GitLab-for-NodeJS_App
This is a simple Node.js application set up for Continuous Integration/Continuous Deployment (CICD) using GitLab CI/CD.
## Prerequisites
- Node.js
- npm

## Installation
1. Clone the repository.
2. Run `npm install` to install dependencies.

## Usage
- To start the application locally, run `node app.js`.
- The application will be accessible at `http://localhost:8080`.

## Continuous Integration/Continuous Deployment (CICD)
This project is configured for CICD using GitLab CI/CD. It consists of two stages:
1. **Build Stage**: Installs dependencies and prepares artifacts.
2. **Deploy Stage**: Deploys the application.

## How to Run CI/CD Pipeline
- Make sure you have access to a GitLab repository with CI/CD configured.
- Push your changes to the repository.
- GitLab CI/CD will automatically trigger the pipeline.
- Check the pipeline status in the GitLab dashboard.
