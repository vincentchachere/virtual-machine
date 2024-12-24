<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

# Microsoft Azure
Azure is Microsoft's cloud computing platform, offering a wide range of services and resources accessible through an online portal. With an internet connection, you can manage and deploy these resources via the Azure portal. This guide will show you how to create an Azure account and set up a virtual machine.

## Requirements

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

## Configuration Steps

- Create an Azure Account
- Create a Resource Group
- Create a Storage Account
- Create a Virtual Machine
- Remote Desktop (RDP) into the Virtual Machine

### Step 1: Create an Azure Account

- Create your Azure account: [here](https://azure.microsoft.com/en-us/free/)

- Select: `Start Free`

  - *Follow the prompt to create account*

  - *To use Azure, you'll need to provide a credit card, but you'll receive $200 in free credits valid for 30 days. Charges only begin once the credits are used up or the 30 days expire*

  - *Finish the prompt*

- Now you are ready to begin!

*To start you can also go to:* [portal.azure.com](https://www.portal.azure.com)

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/6e6b2c44-9e10-4bec-8285-65602c6cded8"><br>

<br>
<br>

<ins>Create an Azure Account</ins>:

- Click: `Go to Azure Portal`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/6c62e0c8-4d65-4d03-bc15-cafff0f51f6d"><br>

<br>
<br>

### Step 2: Create a Resource Group

- Go to the search bar and search: `Resource Group`

  Or..

- Select: `Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/b607495a-8387-4772-bf0e-6797e3ab49ac"><br>

<br>
<br>

<ins>Create a Resource Group</ins>:

- Azure Subscription: `Azure subscription 1`

- Resource Group Name: `RG-Lab1`

- Region: `(US) West 3`

- Select: `Review + Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/f1ee7335-67e5-4e26-8ef5-952ec7836bcf"><br>
<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/7726c51a-d8fe-4bf2-9ea4-4ce76bf3e9d2"><br>

<br>
<br>

### Step 3: Create a Storage Account

- Go to the search bar and search: `Storage Account`

  Or..

- Select: `Create Storage Account`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/4f3182fd-ce97-4c0c-97c3-c5ef5df8e330"><br>

<br>
<br>

<ins>Create a Storage Account</ins>:

- Storage Group Name: `rglab1`
    
  - *Use the same resource group as step 2:* `RG-Lab1`
  - *Use the same region as step 2:* `(US) West 3`

- Select: `Review + Create`

- Select: `Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/9049a3b5-0c53-4be3-a69f-b98d5e0fb947"><br>

<br>
<br>

### Step 4: Create a Virtual Machine
     
- Go to the search bar and search: `Virtual Machine`

  Or..

- Select: `Create` then..

- Select: `Azure Virtual Machine`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/28271ee0-d245-4af1-ab8a-a1a574d1cc10"><br>

<br>
<br>

<ins>Create a Virtual Machine</ins>:

*Fill in everything displayed in the image below.*

- Select Rsource Group Name: `RG-Lab1` (The one you just created)

- Region: `(US) West 3` (*Same region you selected in step 3*)

- Username: `labuser`

- Password: `Create Your Own` (*something you can easily remember*)

- Check: `Licensing Box`

- Click: `Review + Create`

- Click: `Create`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/b6d6fdb3-483b-4838-a2f9-606b87d94453"><br>

<br>
<br>

### Step 5: Connect to the Virtual Machine

<ins>Now we will Remote Desktop (RDP) into the virtual machine we just created by copying vm-1's Public IP Address</ins>:

- Go To: `Resource Groups`

- Select: `RG-Lab1`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/798b7a4b-5666-4739-bf38-4f436a96e55e">

<br>
<br>

<ins>Connecting to the Virtual Machine</ins>:

  - Select: `vm-1`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/3c45bf6c-6703-4f19-be57-c970d2978e63">

<br>
<br>

<ins>Connecting to the Virtual Machine</ins>:

- Copy: vm-1's `public IP address`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/294136a6-0ae1-4007-a60b-7a86213b447b">

<br>
<br>

<ins>Connecting to the Virtual Machine</ins>:

- For Windows Users:

  - Open and use: `Remote Desktop`
 
  - Paste: the `public IP Address`
    
  - Then select: `Connect`
 
  - Enter: the `username and password` (*the one you made when creating vm-1*)
     
  - Select: `OK`

- For Mac Users:

  - Download: `Microsoft Remote Desktop`

  - Open: `the application`

  - Click: `Add PC`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/271b5f3f-f11e-41a7-890d-17b2aabfb9b1"><br>

<br>
<br>

<ins>Connecting to the Virtual Machine</ins>:

- Paste: vm-1's `Public IP ddress`

  - Select: `Add`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/648eef73-ad7e-45d2-8a5e-2418e79f932c"><br>

<br>
<br>

<ins>Connecting to the Virtual Machine</ins>:

- Right-Click: the `Virtual Machine Account`

- Click: `Connect`

- Enter: `the username and password` (*from step 4*)

- Select: `Continue`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/490fe7f1-1088-4f7b-be41-29cb2d50f1ab"><br>

<br>
<br>

<ins>Connecting to the Virtual Machine</ins>:

- Uncheck: `All the Boxes`

- Click: `Accept`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/e59970e9-dd77-4812-984b-4540d90c87c7"><br>

<br>
<br>

🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/virtual-machine/assets/161680745/986ee130-a408-434a-901e-50a6987583c7"><br>

<br>
<br>

### Pro Tip

-  To save your $200 free credits, delete all resources and resource groups once you're done!

☎️ For questions or just to connect you can reach me at: www.linkedin.com/in/vincentchachere
