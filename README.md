
# 🧾 Deploying osTicket – Help Desk Ticketing System

This lab demonstrates the full deployment of **osTicket**, an open-source support ticket system, on a virtual machine hosted in Microsoft Azure. It showcases key skills in cloud provisioning, system configuration, and software deployment — all critical for IT support and sysadmin roles.

---

## 🖼️ Lab Overview (Screenshots + Descriptions)

### 1. Create a Virtual Machine
![Create VM](Ticketing%20Systems(osTicket)/1.%20Creating%20a%20new%20virtual%20machine%20.png)  
Provisioned a Windows 10 Pro VM in Azure to host the osTicket application.

### 2–3. Resource Group & Region
![Resource Group](Ticketing%20Systems(osTicket)/2.%20Create%20a%20new%20resource%20group%20.png)  
Created a new resource group and selected East US 2 for the deployment region.

### 4–5. Choose OS and Specs
![Windows OS](Ticketing%20Systems(osTicket)/4.%20Select%20Windows%2010%20Pro%20.png)  
Selected Windows 10 Pro and configured the VM with at least 8GB RAM.

### 6–8. Network and Deployment
![Deploy VM](Ticketing%20Systems(osTicket)/6.%20Use%20our%20osTicket-vm%20for%20virutal%20network%20then%20click%20review%20and%20create%20.png)  
Attached the VM to a virtual network and completed the deployment successfully.

### 9–10. Connect via RDP
![Public IP](Ticketing%20Systems(osTicket)/9.%20Go%20back%20to%20Virtual%20Machine%20copy%20the%20public%20ip%20adress.png)  
Copied the public IP and connected via Remote Desktop to begin setup.

---

## 🔧 osTicket Installation Steps

### 11. Enable IIS Features
![Enable CGI](Ticketing%20Systems(osTicket)/11.Endable%20CGI.png)  
Enabled IIS, CGI, and necessary Windows features for web hosting.

### 12. Install PHP
![Install PHP](Ticketing%20Systems(osTicket)/12.Install%20PHP.png)  
Installed PHP, a required backend component for osTicket.

### 13. Install HeidiSQL
![HeidiSQL](Ticketing%20Systems(osTicket)/13.install%20HeidiSQL.png)  
Used HeidiSQL to manage the MySQL database for osTicket.

### 14–16. Launch osTicket Installer
![Installer](Ticketing%20Systems(osTicket)/14.osTicket%20installer.png)  
Ran the osTicket setup wizard, resolved PHP extensions, and created the MySQL database.

### 17–18. Finish Setup
![Connected](Ticketing%20Systems(osTicket)/17.connected%20to%20the%20session%20.png)  
Successfully completed the installation and confirmed the help desk system was online.

---

## 🚀 Skills Demonstrated

- Microsoft Azure VM deployment
- Remote Desktop Configuration
- Windows Feature Management (IIS, CGI)
- PHP + MySQL Setup
- osTicket Deployment
- Basic Database Management with HeidiSQL

---

## 💼 Why This Matters

Ticketing systems like osTicket are used in nearly every IT support environment. This lab proves I can independently deploy, configure, and troubleshoot a real-world help desk solution — making me job-ready for roles in IT support and system administration.

---
