# TP Pipelines

## Description:
This repository serves as a demonstration of linting capabilities on GitHub using a Build and Deploy workflow. The repository contains two main workflows: "Build and Deploy" and "Code Linting".

## Build and Deploy Workflow:

    Name: Build and Deploy
    Triggers: Triggered on push to the master branch and pull requests to the master branch.
    Permissions: Write access to repository contents.
    Steps:
        Checkout Repository.
        Set up Node.js.
        Install Dependencies.
        Build Angular App.
        Deploy to GitHub Pages.

## Code Linting Workflow:

    Name: Code Linting
    Triggers: Triggered on pull requests affecting JavaScript or TypeScript files.
    Steps:
        Checkout Repository.
        Set up Node.js.
        Install Dependencies.
        Lint Code.

Both workflows utilize GitHub Actions for automation, ensuring consistent code quality and deployment processes. The "Build and Deploy" workflow focuses on deploying the application, while the "Code Linting" workflow ensures code quality by running a linting process on pull requests.

This repository demonstrates the integration of linting processes into GitHub workflows, aiding in maintaining code quality and consistency within projects.
