# Project Version 1.0

## Working with IaC

This project has been one of the best experiences in my current path to becomming an IT proffesional.
Bicep is a relatively new concept and very smart when it comes to deploying resources into Azure.
I havent had any experience with such a industrial level of coding so i am very grateful for the experience.

Deploying with VS Code has been a great asset to my education on becoming a Cloud Consultant for Microsoft Azure due learning
about the many functions and requirments to have a working Azure infrastructure.
This part of the curricullum has been very challenging and has givin me insight to how much value coding is to understanding
the engineering aspect of cloud infrastructure

## Main project 1.0 resources

- VNETs (2) peered with two seperate subnets protected by NSGs.
- Two separate VMs one Linux and one Windows.
- The two VMs operate separetly in one of the two subnets.
- Encrypted disks for the VMs
- Linux os is for the webserver and Windows os is for the adminserver.
- One recovery vault as backup
- Blob storage with a container holding the bootstrap script.
- Keyvault for encryptions

## 1.0 Bicep architecture
![Bicep Architecture V1 0](https://user-images.githubusercontent.com/89514322/162254312-48664c1c-295a-4555-afe4-1f61efdba48a.png)


## 1.0 Diagram
![Schermopname (5)](https://user-images.githubusercontent.com/89514322/162254328-3cae2d03-cf87-4176-a5fc-1dc68d657266.png)

# Project Version 1.1

## Main project 1.1 resources and new protocols

- VNETs (2) peered with three seperate subnets protected by NSGs.
- Two separate VMs one VMSS Linux and one Windows.
- Appgateway/Loadbalancer.
- Http translation to Https.
- The two VMs operate separetly in one of the two subnets.
- Encrypted disks for the VMs
- Linux os is for the webserver and Windows os is for the adminserver.
- One recovery vault as backup
- Blob storage with a container holding the bootstrap script.
- Keyvault for encryptions

## 1.1 Diagram
![project1 1](https://user-images.githubusercontent.com/89514322/163181479-2170928f-f258-481f-abf0-f3ee09e2498f.jpg)

