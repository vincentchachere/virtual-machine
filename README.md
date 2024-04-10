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

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/6e6b2c44-9e10-4bec-8285-65602c6cded8"><br>

- You can also go to [portal.azure.com](https://www.portal.azure.com) to start

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

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/4f3182fd-ce97-4c0c-97c3-c5ef5df8e330"><br>

- Storage Group Name: `rglab1`
    
  - Use the same resource group as step 2 (RG-Lab1)
  - Use the same region as step 2 ((US) West 3)

- Select: `Review + Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/9049a3b5-0c53-4be3-a69f-b98d5e0fb947"><br>

***

### Step 4: Create a Virtual Machine
     
- Go to the search bar and search: `Virtual Machine`

- Select: `Create`

- Select: `Azure Virtual Machine`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/28271ee0-d245-4af1-ab8a-a1a574d1cc10"><br>

- Resource Group Name: `RG-Lab1`

  - *(Same as the storage group and resource group you created in step 2 and step 3)*

- Virtual Machine Name: `vm-1`

- Region: `(US) West 3`

  - *(Same as the storage group and resource group you created in step 2 and step 3)*

- Availability Type: `No infrastructure redundancy required`

- Security Type: `Standard`

- Image: `Windows 10 Pro, version 22H2 - x64 Gen2`

- *Scroll Down*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/ff81dbed-67a4-496a-b00f-20c7f9c9733e"><br>

- (Disk) Size: `Standard_D4s_v3 - 4 vcpus, 16 GiB memory ($140.16/month)`

- Username: `labuser`

- Password: `Create Your Own`

  - *(something you can easily remember)*

- Select Inbound Ports: `RDP (3889)`

- Click: the `box under licensing`

- Finally click: `Review + Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/a200b9ca-6a1b-4b2c-a29b-4d957817c067"><br>

***

### Step 5: Connect to the Virtual Machine

- First, you will need to find the public IP address of your virtual machine

  - Select: the `virtual machine` we created and the `public IP address` will be on the right-hand side of the screen

  - Copy: the `public IP address`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/8a1abb8e-01e9-4ed4-bdb7-bbd80f957aad"><br>

***

- Windows Users

  - Open and use: `Remote Desktop`
 
  - Paste: the `public IP Address`
    
  - Then select: `Connect`
 
  - Enter: the `username and password from step 4`
     
  - Select: `OK`

- Mac Users

  - Download: `Microsoft Remote Desktop`

  - Open: `the application`
 
  - *Scroll Down*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/95c71740-ea5f-405b-8fd8-4de864853524"><br>

- Click: `Add PC`

- *Scroll Down*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/271b5f3f-f11e-41a7-890d-17b2aabfb9b1"><br>

- Paste: `the public IP address`

  - Select: `Add`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/81206635-7651-48ae-a1a1-7298cd9d1684"><br>

- Double-Click: on the `Virtual Machine Account (the blue ringed rectangle)`

- Click: `Connect`

- Enter: `the username and password` *(from step 4)*

- Select: `Continue`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/4e5eebbc-439f-4fc2-9a77-7623b29064ce"><br>

***

🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/986ee130-a408-434a-901e-50a6987583c7"><br>

***

### Pro Tip

-  If you want to save your free $200 credits, be sure to delete all your resources and resource groups after you finish!

***

☎️ For any questions, concerns, or just to connect you can contact me at:

- 📲 LinkedIn: Vincent Chachere
- 📬 Email: vincent.chachere@gmail.com
