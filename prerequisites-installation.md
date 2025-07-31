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
- Resource Group - Select your resource group
- Virtual machine name - For this lab, we will name our VM:  **"Windows-VM"**
- Region - Select your current region. For this lab, we will select **"(US) East US"**
- Availablity Zone - Select **"Zone 3"**
- Image - Select **"Windows 11 Pro, version 24H2 - x64 Gen2"**
- Size - Select **"Standard_D2s_v3 - 2vcpus, 8GiB memory ($70.08/month)"**

![attachments/6-vm_settings.png](attachments/6-vm_settings.png)

Create your **Administrator account**.

- For this lab, we will use **labuser** as the username and **osTicketPassword1!** as the password.

Check off the Licensing check box

Click **Next: Disks>**, and then **Next: Networking >**

![attachments/7-admin-settings.png](attachments/7-admin-settings.png)

1.4 Click **Create new** under Virtual Network. A window to create a virtual network should pop up

![attachments/8-vnet.png](attachments/8-vnet.png)

Create your **Virtual Network**

- For this lab, we will use **Lab-VNet** as the name of our virtual network

Click **OK** to proceed

![attachments/9-vnet-pt2.png](attachments/9-vnet-pt2.png)

Back on the Virtual Machine page, Click **Review + Create** to proceed  

![attachments/10-review-create.png](attachments/10-review-create.png)

1.5 Confirm that **Validation passed** for your virtual machine.

Review the the information you inputted, ensuring everything is correct.

Click **Create** once more to initialize deployment of your virtual machine.

![attachments/create-vm.png](attachments/create-vm.png)

**A Windows 11 Virtual Machine has now successfully been created.**
