# Week 0 — Billing and Architecture

## Description:

This project aims to build a microservice app that expires content after a set time.

Users will not be tracked and their data and privacy will be protected.

## logical architecture

>This [link](https://lucid.app/lucidchart/e350ef53-cf9d-43d9-866b-602767d07ee0/edit?viewport_loc=-2723%2C-5571%2C4962%2C4674%2C0_0&invitationId=inv_8bfa6f0b-7339-4c79-81f5-bd4a4551747b) displays the logical architecture diagram for the application.

The services and resources that will be deployed  are described  below

>**Amazon Cognito** will be used for authentication. 
>
>**Route 53** is employed to resolve **DNS**. 
>
>**Application Loadbalancer** is used todirect traffic accross the **Containers**. 
>
>**Elastic Container Service(ECS)** is used to host the container where the App resides. 
>
>Databases used are **Amazon Dynamodb** and **Amazon RDS**. 
>
>**Momento** is deployed as a **Serverless cache** while **AppSync**connects the database layer to the **frontend**. 
>
>The **Backend** and **Frontend** communicate using **Rest API**.




