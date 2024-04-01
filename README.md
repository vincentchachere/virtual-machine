<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

# Microsoft Azure
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. This guide will demonstrate how to create an Azure account and create a virtual machine.

## Requirements

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

## Configuration Steps


### Step 1: Create an Azure Account

- Create an Azure account [here](https://azure.microsoft.com/en-us/free/).

- Select: `Start Free`

- Follow the prompt to create the account 

  - You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then

- Finish the prompt

- Click: `Go to Azure Portal`

- Now you are ready to start with Azure!

  - You may also go to [portal.azure.com](https://www.portal.azure.com) to start

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### Step 2: Create a Resource Group

- Go to the search bar at the top and search: `resource group`

- Select: `Create Resource Group`

- Name the resource group and select the region 

- Select: `Review + Create`

  - Towards the lower left

  - For this example, we will be using RG-Lab-1 for the name and (US) West 3 for the region

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### Step 3: Create a Storage Account

- Go to the search bar and search "storage account"

- Select Create Storage Account

- You will need to select the same resource group, the same region, and create a name for the storage group
    
  - For this example, we will name the storage group "rglab1"
    
  - Use the same resource group and region as step 2

- Select Review, then Create

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### Step 4: Create a Virtual Machine
     
- Go to the search bar and search "virtual machine"

- Select Create, then select Azure Virtual Machine

- You will need to select the same resource group, the same region, and create a name for the virtual machine
   
  - For thise example, we will name the virtual machine "virtualmachine"
    
  - Use the same resource group and region as steps 2 and 3

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

- You will then need to select the image and disk size

  - For image we will use Windows 10 Pro
   
  - For size, select See All Sizes and select Standard D2as_v4

- You will then need to make a username and password

  - For username, we will use "labuser"

  - Create your own password

- Click the box under licensing and finally click Review + Create 

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### Step 5: Connect to the Virtual Machine

- First, you will need to find the public IP address of your virtual machine

  - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen

  - Copy the public IP address

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

- Mac Users

  - Download: `Microsoft Remote Desktop`

  - Open: `the application`

  - Click: `Add PC`

  - Paste: `the public IP address`

  - Select: `Add`

  - Double-click: on the `virtual machine`

  - Enter: `the username and password` *from step 4*

  - Select: `Continue`

- Windows Users

     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img width="800" alt="isolated" src=""><br>

***

### Tip

-  If you want to SAVE your FREE $200 CREDITS, be sure to DELETE ALL your RESOURCES and RESOURCE GROUPS AFTER you FINISH!    
  
