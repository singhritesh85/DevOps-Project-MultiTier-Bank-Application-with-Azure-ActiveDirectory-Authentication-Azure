# DevOps-Project-MultiTier-Bank-Application-with-Azure-ActiveDirectory-Authentication-Azure

Architecture diagram for the project is as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/c0eb22ae-e4d0-4eaf-9322-c7ecaafed1ab)

In this project for Authentication of Azure DevOps Pipeline, SonarQube and Azure Artifact Feed I have used Azure Active Directory (Azure AD) as shown in the screenshots attached nelow.

Connect your Azure DevOps Organisation with Azure Entra as shown in the screenshot acched below.

![image](https://github.com/user-attachments/assets/4321872c-3866-49e3-b390-fca95b0f9dc8)

To integrate SonarQube with Azure Active Directory (Azure Entra ID) follow the steps as shown in the screenshot attached below.

Install the plugin for Azure Active Directory in SonarQube as shown in the screenshot shown below.

![image](https://github.com/user-attachments/assets/69a3bf45-2488-4b36-b21e-2c16c890c407)
![image](https://github.com/user-attachments/assets/5464f1ba-9d7b-4c35-87b0-5198466809e7)

Create App Regestration as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/b19e8b8b-16af-4eb3-b5e7-2c2774c48425)
![image](https://github.com/user-attachments/assets/bab86daa-f59b-47ef-ae28-f9d0b0d7c78e)
![image](https://github.com/user-attachments/assets/5004d489-ddc1-4eb4-92aa-e3377d805184)

Configure Server Base URL as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/8c77d2db-64c6-4636-ba46-1fcd0814104d)

Further configuration in SonarQube plugin for Azure Active Directory as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/333e853f-478a-4edc-9d29-e3bc47c5f895)
![image](https://github.com/user-attachments/assets/823005d3-a9e4-440c-8def-999d27d57d17)
![image](https://github.com/user-attachments/assets/e429b469-c794-42b4-a650-d5c28232a2ee)

Finally we can Access the SonarQube as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/72133612-2bbe-4d6c-b8d1-802abdf2043b)
![image](https://github.com/user-attachments/assets/d433484e-bfbd-44bd-b546-446fb22fa1fc)

Provided Administrative privilege as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/9cef79b1-03ac-48f0-9b52-b417ad0cbbb3)
![image](https://github.com/user-attachments/assets/7dc31d11-9092-4baa-9da3-38e7d44f4523)

Integrate Azure Artifact Feed with Azure Entra ID as shown in the screenshot attached below. Provided contributor permission to user for Azure Artifact Feed. 

![image](https://github.com/user-attachments/assets/9fd244ea-7a19-4d94-942c-33d1e113356f)

The Source Code was present in the Azure Repos as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/10383f79-d2e2-457d-9661-85e4ba20c4c9)

Service Connections has been created as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/7010265d-a25c-4ea8-8f63-edcf9401985a)

Azure DevOps Pipeline had been created as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/7b858c33-0743-4200-82a8-8f6b9b4aa7a7)

After running the Azure DevOps Pipeline the screenshot for SonarQube and Azure Artifacts Feed is as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/3eb6c01e-1301-4372-933c-7bb5b5858712)
![image](https://github.com/user-attachments/assets/e0ee2a10-4f16-4b35-bb44-b78562be86df)

Ingress Rule had been created as shown in the screenshot attached below and do the entry in Azure DNS Zone to create the Recordset.

![image](https://github.com/user-attachments/assets/b561bd63-d991-4eef-8e5a-3d71f0cb8bfb)

Finally Access the Application as shown in the screenshot attached below.

![image](https://github.com/user-attachments/assets/97633092-a9e9-4677-aa5b-36118f2abf84)
![image](https://github.com/user-attachments/assets/080ccffa-bc64-4179-9e46-36dd58259cf7)

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
