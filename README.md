# Introduction 
This repository has an example of a dotnet project that is being built and analyzed by the SonarScanner and reporting the results to SonarQube Cloud and SonarQube Server. 

# Getting Started
The SonarScanner for Azure Pipelines requires a Prepare and Analyze step and an optional Publish step.  
There are predefined tasks to be used for Azure Pipelines for both SonarQube Cloud and SonarQube Server.
In order to be able to scan a dotnet project, you need to build the project before it gets scanned by the SonarScanner. 

# Important Links  
SonarQube Server - SonarQubePrepare > https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/sonar-qube-prepare-v7?view=azure-pipelines  
SonarQube Server > https://docs.sonarsource.com/sonarqube-server/latest/devops-platform-integration/azure-devops-integration/  
SonarQube Cloud > https://docs.sonarsource.com/sonarqube-cloud/advanced-setup/ci-based-analysis/sonarcloud-extension-for-azure-devops/  
