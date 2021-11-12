# Vanilla JavaScript App


[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview) allows you to easily build JavaScript apps in minutes. Use this repo with the [quickstart](https://docs.microsoft.com/azure/static-web-apps/getting-started?tabs=vanilla-javascript) to build and customize a new static site.

This repo is used as a starter for a _very basic_ HTML web application using no front-end frameworks.

# Steps

This repo was created from the instructions on this website:

https://docs.microsoft.com/en-us/azure/static-web-apps/getting-started?tabs=vanilla-javascript

# Prerequisites

- GitHub account
- Azure account
- Visual Studio Code
- Azure Static Web Apps extension for Visual Studio Code  (I had to install this in VS Code)
- Install Git

# Setting up a Static Web App

- Use the VS Code Extension -> Click the Azure Icon in the Activity Bar 
- click the + icon
- Enter a name for the app e.g. my-first-static-web-app
- Select the Region (Europe)
- enter ```/src``` as the directory containing the source code
- clear out ```build```
- deploy

This will connect to github and create a github actions workflow for you that will automatically build and deploy to the Azure Static Web App!

Final Deploy URL:

https://white-meadow-0006bf903.azurestaticapps.net/

# Visio Code - Parameter Bar

- Use Ctrl + Shift + P to open up the command bar
- You can then type in ```git: commit``` or ```git: push``` to interact with github

# References

[What is Azure Static Web Apps?](https://docs.microsoft.com/en-us/azure/static-web-apps/overview)