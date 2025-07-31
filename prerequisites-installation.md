# osTicket - Prerequisites and Installation
This tutorial outlines the prerequisites aand installation of the help desk ticketing system: osTicket.

## Installation Steps

*NOTE: Ensure that you are logged into your Microsoft Azure account, have a subscription active and have already made a resource group for your virtual machine.*

---

## Table of Contents
- Create a new Virtual Machine within Azure
- Installing osTicket prerequisites
- Installing osTicket
- Configuring osTicket
- Exploring osTicket as a Help Desk Professional

---
### Step 1: Create a new Virtual Machine within Azure

1.1 Search for "Virtual Machine" in the search bar, or navigate to the Virtual Machine section back on the home page.

![attachments/4-VM.png](attachments/4-VM.png)

1.2 On the Virtual Machine page, click **Create**, and then select **Virtual machine**.

![attachments/5-VM_Create.png](attachments/5-VM_Create.png)

1.3 Fill out the following information:
- Subscription - Select your current and active subscription
- Resource Group - Select your resource group/make a new one
- Virtual machine name - For this lab, we will name our VM:  **"osticket-vm"**
- Region - Select your current region. For this lab, we will select **"(US) East US"**
- Availablity Zone - Select **"Zone 3"**
- Image - Select **"Windows 11 Pro, version 24H2 - x64 Gen2"**
- Size - Select **"Standard_D2s_v3 - 2vcpus, 8GiB memory ($70.08/month)"**

![attachments/6-vm_settings.png](attachments/6-vm_settings.png)

Create your **Administrator account**.

- For this lab, we will use **labuser** as the username and **osTicketPassword1!** as the password.

Check off the Licensing check box

Click **Review + Create** to proceed

![attachments/7-admin-settings.png](attachments/7-admin-settings.png)

1.3 Confirm that **Validation passed** for your virtual machine.

Review the the information you inputted, ensuring everything is correct.

Click **Create** once more to initialize deployment of your virtual machine.

![attachments/create-vm.png](attachments/create-vm.png)

**A Windows 11 Virtual Machine has now successfully been created.**

## Step 2: Use Remote Desktop to connect to your Windows 11 Virtual Machine

2.1 On your Virtual Machine page within Azure, you will be able to see the designated Public IP Address for each virtual machine created.

Use the Windows 11 Virtual Machine's IP address to log in through Remote Desktop

![attachments/public-ip.png](attachments/public-ip.png)

![attachments/rdp.png](attachments/rdp.png)

2.2 A small windows security prompt will ask you to enter your credentials to log into the virtual machine

- We will use the username and password that we made when creating the virtual machines **(labuser/Cyberlab123!)**

![attachments/pw.png](attachments/pw.png)

Another windows prompt will appear, click **Yes** to proceed

![attachments/yes.png](attachments/yes.png)

Power on the Windows 11 virtual machine and proceed with the setup steps until you reach the Windows Desktop.

![attachments/window-desktop.PNG](attachments/window-desktop.PNG)
