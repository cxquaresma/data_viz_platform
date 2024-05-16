# Setup

- Using Pipenv for virutal env
-- run: pipenv --python 3.11 to setup
-- package in pipfile, when changing run : pipenv install

## TO DO

1. set up a new React application using Create React App or your preferred method for front end. (make sure the file_upload.js aligns)

2. setup the MVP


2. CICD setup
Setting up CI/CD with GitHub Actions:

    Create Workflow Files: In your project repository, create YAML files to define your CI/CD workflows. These files are stored in the .github/workflows directory.

    Define Workflow Steps: Define the steps you want to execute in your workflow, such as installing dependencies, running tests, building the application, and deploying to your hosting environment.

    Trigger Events: Specify the events that trigger your workflows, such as pushes to specific branches, pull requests, or cron jobs for scheduled builds.

    Use GitHub Actions Marketplace: Explore the GitHub Actions Marketplace to find pre-built actions and workflows that suit your needs. There are many community-contributed actions available for various tasks like testing, code formatting, and deployment.

    Secrets Management: Use GitHub Secrets to securely store sensitive information like API keys, access tokens, and deployment credentials. These secrets can be accessed from your workflows during the build and deployment process.

    Testing and Deployment: Configure your workflows to run automated tests on every code change and deploy the application to your hosting environment after successful tests.