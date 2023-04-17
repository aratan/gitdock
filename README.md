

# GitDock
Automate your Docker deployments with GitDock! This command-line interface (CLI) tool monitors your GitHub repositories for new commits and automatically builds and pushes Docker images to Docker Hub. With GitDock, you can streamline the deployment process and easily manage your containerized applications.

# Getting Started
## To get started with GitDock, you'll need to have a few things set up:

A GitHub account and repository with a Dockerfile and Docker Compose file.
A Docker Hub account and a repository with the same name as your GitHub repository.
A personal access token from GitHub with repo and read:user scopes.
Your Docker Hub login credentials.
Once you have everything set up, you can install GitDock and start deploying your containers! Here's how to use GitDock:

gitdock <token> <user> <repo> <branch>
<token>: Your GitHub personal access token.
<user>: Your Docker Hub username.
<repo>: The name of your GitHub repository.
<branch>: The name of the branch you want to monitor for changes (usually main or master).
<e-mail>: The e-mail Alert.
For example:

gitdock abc123 myusername myproject main john@mesdt.com
Features
GitDock offers the following features:

Automated Docker deployments based on GitHub commits.
Support for Dockerfiles and Docker Compose files.
Streamlined deployment process.
Easy management of containerized applications.
Conclusion
If you're looking for a way to automate your Docker deployments, GitDock is the tool for you! With its easy setup process and streamlined deployment process, you can focus on developing your applications and let GitDock handle the rest. Try it out today!
