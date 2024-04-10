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
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/6e6b2c44-9e10-4bec-8285-65602c6cded8"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/6c62e0c8-4d65-4d03-bc15-cafff0f51f6d"><br>

***

### Step 2: Create a Resource Group

- Go to the search bar and search: `resource group`

- Select: `Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/b607495a-8387-4772-bf0e-6797e3ab49ac"><br>

- Resource Group Name: `RG-Lab1`

- Region: `(US) West 3`

- Select: `Review + Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/f1ee7335-67e5-4e26-8ef5-952ec7836bcf"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/7726c51a-d8fe-4bf2-9ea4-4ce76bf3e9d2"><br>

***

### Step 3: Create a Storage Account

- Go to the search bar and search: `Storage Account`

- Select: `Create Storage Account`

- Storage Group Name: `rglab1`
    
  - Use the same resource group as step 2 (RG-Lab1)
  - Use the same region as step 2 ((US) West 3)

- Select: `Review + Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/4f3182fd-ce97-4c0c-97c3-c5ef5df8e330"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/f9dcab68-9530-4db3-94a4-387aaa21369c"><br>

***

### Step 4: Create a Virtual Machine
     
- Go to the search bar and search: `virtual machine`

- Select: `Create`

- Select: `Azure Virtual Machine`

- You will need to select the same resource group, the same region, and create a name for the virtual machine

  - For this example, we will name the virtual machine: `vm-1`
    
  - Use the same resource group and region as steps 2 and 3

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/9ffa08bf-c277-4b06-afeb-4ed5bbe9ab8b"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/6e127285-8f1b-421f-a0a3-119d908c368a"><br>

***

- You will then need to: `select the image and disk size`

  - For the image we will use: `Windows 10 Pro`
   
  - For the size select: `See All Sizes`
 
  - Then select: `Standard D2as_v4`

- You will then need to make a username and password

  - Username: `labuser`

  - Password: `Create Your Own` *(something you can easily remember)*

- Click: the `box under licensing`

- Finally click: `Review + Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/297a27e0-d781-4189-a304-59dd419e65f3"><br>

***

### Step 5: Connect to the Virtual Machine

- First, you will need to find the public IP address of your virtual machine

  - Select: the `virtual machine` we created and the `public IP address` will be on the right-hand side of the screen

  - Copy: the `public IP address`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/ba046ebd-bd8d-4a41-b5d2-961d2f683720"><br>

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

  - Open and use: `Remote Desktop`
 
  - Paste: the `public IP Address`
    
  - Then select: `Connect`
 
  - Enter: the `username and password from step 4`
     
  - Select: `OK`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/5152435e-5e57-4728-8e97-545e764be345"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/d81f8c96-75e7-4234-b55b-f79c3d14854b"><br>

***

🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/986ee130-a408-434a-901e-50a6987583c7"><br>

***

### Tip

-  If you want to save your free $200 credits, be sure to delete all your resources and resource groups after you finish!    
  
