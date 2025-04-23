
# 🧾 Deploying osTicket on Azure – Full Walkthrough with Screenshots

This project walks through the full deployment and configuration of **osTicket**, a popular open-source support ticketing system. You'll see how to provision a Windows 10 VM in Azure, configure it for web hosting, install PHP and MySQL, and finalize the osTicket setup.

---

## 🧰 Technologies Used

- **Microsoft Azure** – Cloud platform used to host the virtual machine.
- **Windows 10 Pro VM** – OS for the deployment.
- **Remote Desktop Protocol (RDP)** – To access and manage the VM.
- **Internet Information Services (IIS)** – Web server for hosting osTicket.
- **PHP** – Backend language required for osTicket.
- **MySQL** – Database for storing ticketing data.
- **HeidiSQL** – GUI tool to manage the MySQL database.
- **osTicket** – The help desk ticketing system being deployed.

---

## 🖼️ Step-by-Step Guide (with Screenshots)

### 🔹 Step 1: Create a Virtual Machine
![Step 1](Ticketing%20Systems(osTicket)/1.%20Creating%20a%20new%20virtual%20machine%20.png)  
Go to Azure portal → Virtual Machines → Create. Name the VM and select your resource group.

---

### 🔹 Step 2: Create a Resource Group
![Step 2](Ticketing%20Systems(osTicket)/2.%20Create%20a%20new%20resource%20group%20.png)  
Create a new resource group to organize all resources related to osTicket.

---

### 🔹 Step 3: Choose the Region
![Step 3](Ticketing%20Systems(osTicket)/3.%20East%20US%202%20.png)  
Select a close and cost-efficient region. East US 2 is often a good default.

---

### 🔹 Step 4: Select Windows 10 Pro as the OS
![Step 4](Ticketing%20Systems(osTicket)/4.%20Select%20Windows%2010%20Pro%20.png)  
Choose Windows 10 Pro so you can install desktop applications.

---

### 🔹 Step 5: VM Specs
![Step 5](Ticketing%20Systems(osTicket)/5.%20Pick%20at%20least%208gb%20of%20ram%20and%20check%20the%20box.png)  
Make sure you choose a size with enough RAM (at least 8GB) for installation tasks.

---

### 🔹 Step 6–7: Configure Virtual Network & Deploy
![Step 6](Ticketing%20Systems(osTicket)/6.%20Use%20our%20osTicket-vm%20for%20virutal%20network%20then%20click%20review%20and%20create%20.png)  
Attach the VM to an existing or new VNet and click "Review + Create."

![Step 7](Ticketing%20Systems(osTicket)/7.%20Cick%20create%20button.png)  
Click "Create" to deploy your VM.

---

### 🔹 Step 8: Wait for Deployment
![Step 8](Ticketing%20Systems(osTicket)/8.%20Deployment%20complete%20.png)  
Deployment complete!

---

### 🔹 Step 9–10: Access VM Using Public IP
![Step 9](Ticketing%20Systems(osTicket)/9.%20Go%20back%20to%20Virtual%20Machine%20copy%20the%20public%20ip%20adress.png)  
Copy your public IP address.

![Step 10](Ticketing%20Systems(osTicket)/10.%20Open%20Remote%20Desktop%20and%20paste%20the%20public%20ip%20adress%20into%20computer%20name%20.png)  
Open RDP on your local PC and paste the IP to connect.

---

### 🔹 Step 11: Enable IIS and CGI
![Step 11](Ticketing%20Systems(osTicket)/11.Endable%20CGI.png)  
Install IIS from "Turn Windows features on or off." Enable:
- Internet Information Services
- CGI
- Common HTTP Features

---

### 🔹 Step 12: Install PHP
![Step 12](Ticketing%20Systems(osTicket)/12.Install%20PHP.png)  
Download and install PHP. Ensure it’s properly linked to IIS.

---

### 🔹 Step 13: Install HeidiSQL
![Step 13](Ticketing%20Systems(osTicket)/13.install%20HeidiSQL.png)  
Install HeidiSQL to manage your MySQL database.

---

### 🔹 Step 14: Run osTicket Installer
![Step 14](Ticketing%20Systems(osTicket)/14.osTicket%20installer.png)  
Access the osTicket web installer via browser (e.g., http://[public-ip]/upload) and follow the steps.

---

### 🔹 Step 15: Fix PHP Extensions
![Step 15](Ticketing%20Systems(osTicket)/15.PHPextension.png)  
Make sure all required PHP extensions are installed (e.g., IMAP, GD, XML).

---

### 🔹 Step 16: Create a MySQL Database
![Step 16](Ticketing%20Systems(osTicket)/16.create%20a%20database.png)  
Create a database using HeidiSQL to be used by osTicket.

---

### 🔹 Step 17–18: Finalize and Connect
![Step 17](Ticketing%20Systems(osTicket)/17.connected%20to%20the%20session%20.png)  
Complete the installer with admin credentials and database info.

![Step 18](Ticketing%20Systems(osTicket)/18.FINISHED%20.png)  
osTicket is now live and ready to use.

---

## 💼 Final Thoughts

This lab demonstrates real-world IT support skills — from provisioning cloud VMs to configuring web servers and deploying internal ticketing solutions. This type of project directly applies to help desk, system admin, and IT support roles in the industry.

---
