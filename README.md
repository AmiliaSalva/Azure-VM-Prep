# Setting up VMs in Azure

![azurebanner](https://github.com/AmiliaSalva/Azure-VM-Prep/assets/132176058/8f3a67f3-0480-445c-8a4a-021b666e2af2)

### To kick off our Azure Honeynet project, we first need to set up the virtual machines (VMs) we'll be using. Virtual machines are like computers in the cloud, and they'll form the foundation of our honeynet. I'll guide you through the process so you can understand how it's done. Here are the steps we'll take in Microsoft Azure:

1. **Sign in to the Azure portal:** The first step is to log into your Azure account. If you don't have an account yet, **[you'll need to create one!](https://portal.azure.com)**

<details close> 
<summary> 2. Create a virtual machine: </summary>




- Once you're in the Azure portal, navigate to the 'Virtual machines' section. 
  
  ![azure portal](https://github.com/AmiliaSalva/Azure-VM-Prep/assets/132176058/89174131-d43a-444b-b3f9-e4b7972d0041)

  
  
- Click on 'Create', then 'Virtual machine'. This is where we'll set up our new VM!
  
 
  ![VM create](https://github.com/AmiliaSalva/Azure-VM-Prep/assets/132176058/f8cc721b-2439-4390-9552-06a51b996918)
  
  </details>
  
  
  <details close> 
<summary> 3. Configure the VM settings: </summary>
  
  - **Subscription and resource group:** We'll select our Azure subscription and resource group (Which is way to group and manage resources in Azure!). For the purpose of the project, I already created created a resource group called ```RG-Cyber-Lab2``` 
  
  - **Virtual Machine Name:** For the purpose of this project, I am going to name this VM, ```Lab-HoneyNet```

  - **Region:** For the purpose of this project, I am going to choose the region, ```(US) East US 2```
  
  - **Availability Options:** Being that the only purpose of this machine will be to act as a Honeypot, we do not require any form of availability, so I selected ```No infrastructure redundancy required```

  - **Image:** Select ```Windows 10 Pro, version 21H2 - x64 Gen2```
  
  ![VM create](https://github.com/AmiliaSalva/Azure-VM-Prep/assets/132176058/10525f40-6634-4cef-b519-0487d492c878)
  
  - **Networking**: When creating the virtual network, we will be leaving it to the default settings. For the purpose of this lab, I called mine ```Lab-VNet```.
  
  ![netowkr](https://github.com/AmiliaSalva/Azure-VM-Prep/assets/132176058/8fe63ac8-42a9-4bea-bab0-2575013c185c)


  </details>
