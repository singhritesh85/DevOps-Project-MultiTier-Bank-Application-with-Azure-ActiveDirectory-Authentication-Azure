# DevOps-Project-MultiTier-Bank-Application-with-Azure-ActiveDirectory-Authentication-Azure

Architecture diagram for the project is as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/c0eb22ae-e4d0-4eaf-9322-c7ecaafed1ab)

In this project for Authentication of Azure DevOps Pipeline, SonarQube and Azure Artifact Feed I have used Azure Active Directory (Azure AD) as shown in the screenshots attached nelow.

Connect your Azure DevOps Organisation with Azure Entra as shown in the screenshot acched below.

![image](https://github.com/user-attachments/assets/4321872c-3866-49e3-b390-fca95b0f9dc8)



![image](https://github.com/user-attachments/assets/69a3bf45-2488-4b36-b21e-2c16c890c407)





```
The bankapp-auth secrets for kubernetes can be created using the command below

kubectl create secret docker-registry bankapp-auth --docker-server=https://bankappcontainer24registry.azurecr.io --docker-username=bankappcontainer24registry --docker-password=qXXXXXXXXXXXXXXXXrCHXXXXXXXXXXXXXXXXV0zXXXXXXXXXXXX7 -n bankapp
```
<br><br/>
<br><br/>
```
OpenJDK Docker Image is depricated so in this project eclipse-temurin docker image has been used as a base image in the Dockerfile. 
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Source Code:-  https://github.com/singhritesh85/Bank-App.git
```
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://github.com/Goldencat98/Bank-App.git
```
