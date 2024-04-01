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

- Create your Azure account [here](https://azure.microsoft.com/en-us/free/)

- Select: `Start Free`

  - *Follow the prompt to create account*

  - *You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then*

  - *Finish the prompt*

- Click: `Go to Azure Portal`

- Now you are ready to begin!

  - *You can also go to [portal.azure.com](https://www.portal.azure.com) to start*

<p align="center">
<img width="800" alt="isolated" src="https://camo.githubusercontent.com/1f295ebe480222ffc5cc8c8bc66fd4ff49a963d9719f4e5eb9bbdc79c973febc/68747470733a2f2f692e696d6775722e636f6d2f726b34534432372e706e67"><br>
<p align="center">
<img width="800" alt="isolated" src="https://camo.githubusercontent.com/7a69e290ae4e79ca235cfd35e8183a545101fc8fb3310009dff0676727086d3b/68747470733a2f2f692e696d6775722e636f6d2f663165524978342e706e67"><br>

***

### Step 2: Create a Resource Group

- Go to the search bar at the top and search: `resource group`

- Select: `Create Resource Group`

  - Name the resource group and select the region 

- Select: `Review + Create`

  - *Towards the lower left*

- For this example, we will be using:

  - Name: `RG-Lab1`

  - Region: `(US) West 3`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/31f5770a-72d6-494d-a2b5-cc6ffceec609"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/c2a43bfc-d498-46c4-8c5b-3316b83a496e"><br>

***

### Step 3: Create a Storage Account

- Go to the search bar and search: `storage account`

- Select: `Create Storage Account`

  - You will need to select the same resource group, the same region, and create a name for the storage group

- Storage Group Name: `rglab1`
    
  - Use the same resource group and region as step 2

- Select: `Review`

- Select: `Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/9ae27541-d993-4021-9fd4-8922e27c5065"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/f9dcab68-9530-4db3-94a4-387aaa21369c"><br>

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
  
