<p align="center">
<img src="https://i.imgur.com/3iwtTkN.jpeg height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>


# Creating a Virtual Machine Using Azure


## Prerequisites and Installation

This tutorial outlines the prerequisites and installation steps for Creating a Virtual Machine Using Azure

## Environments and Technologies Used
 **Azure Portal**
- **The Azure Portal is the main web interface for creating, configuring, and managing Azure VMs and other resources** 
- **Usage: It offers a visual interface to select VM types, configure networking, assign storage, set up security, and manage monitoring options**


## Operating Systems Used
-  **Azure VMs can run Windows Server for enterprise and web hosting, various Linux distributions like Ubuntu, CentOS, and RHEL for open-source projects and development, while macOS can be used for connecting to and managing VMs using tools like Azure CLI and PowerShell** 

## List of Prerequisites

- **Azure Account** 
- **Computer with Internet Connection**
- **Credit Card (Required for free Azure credits)**

## Installation Steps

### Step 1: Create an Azure Account 


1. Create an Azure account [here](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account?icid=azurefreeaccount)
2. Follow the prompt to create the account
3. You will need to put in your credit card information for verification purposes, this will allow you to get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then
4. Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!
    
### Additionally If You Already Have An Account Go [Here](https://www.portal.azure.com) To Start
&nbsp;

![Azure Sign Up](https://i.imgur.com/jhPlHcM.png)

### Azure Portal Login
![Azure Portal Login](https://i.imgur.com/5xXXBKu.png)

### Step 2: Create a Resource Group  

1. Go to the Azure portal search bar at the middle top of the screen and search **resource group**
2. Select Resource Groups
![Azure RG](https://i.imgur.com/RoeNEDQ.png)
3. In the Resource Groups tab click **Create** on the left top side of the screen or on the bottom middle
![Azure RG](https://i.imgur.com/1U1NmMl.png)
5. We then need to name the resource group and select a region
6. In this tutorial we will name the resource group **resourcegroup1** and select **(US) East US** for the region
7. On the bottom left of the screen click **Review + Create**
![Azure RG](https://i.imgur.com/6WO3Ffb.png)
(it should say Azure subscription 1 if using a brand new account)
9. Once verification is complete we have successfully created a Resource Group. We can then click **Create** at the bottom right of the screen
&nbsp;



![Azure RG](https://i.imgur.com/vUn410f.png)
![Azure RG](https://i.imgur.com/2EZSOat.png)

### Step 3: Create a Storage Account
1. Go to the Azure portal search bar at the middle top of the screen and search **Storage Accounts**
2. Select **Storage Accounts**
3. Click **Create** on the left top side of the screen or on the bottom middle
![Azure RG](https://i.imgur.com/Eeygknm.png) 
4. We need to select the same **Resource Group and Region we used in step 2**
5. In this tutorial we will name the Storage Account **storageaccount1** and select **(US)East US** for the region
6. At the bottom left of the screen we will select **Review + Create** and in the next one click **Create**
![Azure RG](https://i.imgur.com/y95jXBl.png)
![Azure RG](https://i.imgur.com/D0xT4ET.png)
7. Our Storage Account is now successuccessfully fully created
&nbsp;



### Step 4: Create a Virtual Machine
1. Go to the Azure portal search bar at the middle top of the screen and search **Virtual Machines**.
2. Select **Virtual Machines**
![VM](https://i.imgur.com/Znvhn2a.png)
3. Click Create Azure Virtual Machine at the middle bottom of the screen of the page
![VM](https://i.imgur.com/g8Nd8SJ.png)
4. We will need to select the same **Resource Group**, **Region**, and create a name for the virtual machine
5. In this tutorial, we will name the virtual Machine **"Windows10ProVM"**
![VM](https://i.imgur.com/VlfgZCZ.png)
6. We now need to select an Image for our virtual machine
7. In this tutorial, we will be using a **Windows 10Pro VM image**
![VM](https://i.imgur.com/Ffi9sTU.png)
8. Next scroll down to size , we need to select a VM size with 2vcpus
9. Finally, we will create a username and password so we can login to our VM
![VM](https://i.imgur.com/I9lXRRf.png)
10. Make sure to confirm and agree to licensing agreements 
11. Once validation is passed we have now successfully  created our VM
![VM](https://i.imgur.com/B9KSSRc.png)
![VM](https://i.imgur.com/5KfUJPb.png)
&nbsp;



### Step 5: Connect to the Virtual Machine (Windows)
1. First we need to find the public IP Address of our virtual machine
2. Select the virtual machine we created and copy the public IP Address on the right side of the Virtual Machine of the screen
![VM](https://i.imgur.com/3dlD3Ea.png)
3. Open up Remote Desktop Connection or type **MSTSC** in the search bar
![VM](https://i.imgur.com/FUMEMaf.png)
4. In Remote Desktop Connection we can then now paste in  our IP Address
![VM](https://i.imgur.com/kSmOE3Z.png)
&nbsp;



### Step 6: Connect to the Virtual Machine
1. Enter the username and password from step 4
![VM](https://i.imgur.com/mVm8WEE.png)

2. Congratulations! You have created your first virtual machine within Azure!
![VM](https://i.imgur.com/wEaETOZ.png)


### Mac Users
1. Download **Windows App** from the App Store
![VM](https://i.imgur.com/2RMyI4D.png)
2. Open the application and click the **+** sign and then **Add PC**
![VM](https://i.imgur.com/bU2UG05.png)
3. Paste the public IP address from the created Virtual Machine on **PC Name** and select Add

<p align="center">
<img src="https://i.imgur.com/DowLpto.png" height="70%" width="70%"/>
</p>

4. Double-click on the virtual machine and enter the username and password from step 4
![VM](https://i.imgur.com/UGLefZM.png)

5. Congratulations! You have created your first virtual machine within Azure!
![VM](https://i.imgur.com/wEaETOZ.png)

## Conclusion
🎉You’ve successfully created a Vitrual  Machine in Azure🎉
