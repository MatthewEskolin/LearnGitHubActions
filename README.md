# LearnGitHubActions
GitHub Actions Examples

I am learning how to use GitHub Actions

First, I need a way to deploy code to an Azure Virtual Machine when the code is pushed to github. I had been using Azure Pipelines for this purpose, but I like the simplicity of having the code and the deployment logic stored on github together, instead of using azure pipelines to pull the code from github, and then deploy it. Using a github action removes an intermediary system.


#change to run workflow

7/16/2022
https://docs.microsoft.com/en-us/azure/app-service/deploy-github-actions?tabs=openid
use this to create service principal for our new app
