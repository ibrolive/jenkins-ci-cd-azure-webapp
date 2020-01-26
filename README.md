# Emirates Jenkins CI/CD Azure WebApp

This repository contains infrastructure as code template to setup jenkins server on Azure webapp. 
Jenkins build is triggered on each commit to the project repository. 
After each build, Jenkins releases application to webapp with MySQL database. 
Grafana displays visualization of infrastructure and application metrics via Azure Monitor.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fibrolive%2Femirates-jenkins-ci-cd-azure-webapp%2Fmaster%2Fazuredeploy.json" rel="nofollow">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png" style="max-width:100%;">
</a>

<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fibrolive%2Femirates-jenkins-ci-cd-azure-webapp%2Fmaster%2Fazuredeploy.json" rel="nofollow">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png" style="max-width:100%;">
</a>