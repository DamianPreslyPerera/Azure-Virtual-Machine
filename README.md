  ![1572653575_azure_vm_story](https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/a0dfbb3c-486c-4c48-b76b-a924e6c66ef1)


# Azure Virtual Machine

This project provides a concise guide to setting up and connecting to a virtual machine in Microsoft Azure. Through this demonstration, users will learn to create an Azure Resource Group, configure a virtual machine, and establish a connection to it using the Remote Desktop Protocol (RDP). This project primarily focuses on the key steps required to quickly deploy and access virtual machines within the Azure cloud environment, making it an ideal starting point for those looking to harness the capabilities of Azure VMs.


## Environments and Technologies Used

* Microsoft Azure
* Remote Desktop



## Operating Systems Used 

* Windows 10



## High-Level Steps

* Create MS Azure Resource Group
* Virtual Machine Configuration
* Connect to Virtual Machine with Remote Desktop

---

### MS Azure Resource Group Creation

![image](https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/6bd05d97-e095-4e46-98bc-7c2debc5b3ec)

* Navigate to the Azure Portal and click on "Resource Groups"

---

![image](https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/b97e1dae-3873-4037-b01b-bbd1b7c9340c)

* Click on the "Create" Button

---

![image](https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/68b62359-386e-40dd-8e9e-e82f277f1dec)

* Choose a preffered Azure Subscription and name your Resource Group

---

![image](https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/2156e68d-78c9-4500-ba6a-0e4e931c6c17)

* Create your resource group

---

<img width="1128" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/f758bf57-d7eb-489a-abaa-6d9fc4a62317">

* You should be able to view your Resource Group within the Azure Portal now


---
### Virtual Machine Creation

<img width="1128" alt="Screenshot 2023-10-02 VMportal" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/64cad676-00dc-42ba-ba86-8aba623a84d2">

* Click on the Virtual Machine icon in the Azure Portal

---

<img width="1128" alt="Screenshot 2023-10-02 110320vm2" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/2dcef8f2-a03c-4c34-bb7d-7b51320168f6">

* Click on the "Create" Button

---

<img width="259" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/487ff3d9-0955-4c54-aa76-3bc8968be628">

* Click on "Azure Virtual Machine"

---

<img width="595" alt="Screenshot 2023-10-02 110718vmconf1" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/a9cffd95-f621-439c-adc1-a8dc3b7d83c4">

* Choose the Resource Group you created before, then type in a name for the virtual machine

---

<img width="584" alt="Screenshot 2023-10-02 111002vmcreds" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/04cce67c-a2a0-48f7-ac0c-f8ea3894a44e">

* Choose the Windows 10 image, and choose whichever size you prefer, and create login credendtials 

---

<img width="1128" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/dc2b6024-2a08-47ff-a618-4878990a828c">

* After clicking "Review + Create", you should be able to view your Virtual Machine
* Copy the IP Address of your Virtual Machine
* You will be using the IP Address to connect to the machine from remote desktop
  
---

### Connect to Virtual Machine with Remote Desktop

<img width="303" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/6d3ca337-7907-43fd-90b3-32cd902687d1">

* Open the Remote Desktop application on your computer
* Type in the IP Address of your Virtual Machine
* Click on "Connect"

---

<img width="336" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/704502f3-38b4-4663-bd0e-a546ea2d9de9">

* You will be presented with a prompt to enter your credentials
* These are the credentials you created when making your Virtual Machine

---

<img width="293" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/57202f87-d646-4746-840f-866de8c9b24d">

Click "Yes" when presented with this prompt

---

## Congratulations! You have just made a virtual machine!

<img width="1116" alt="image" src="https://github.com/DamianPreslyPerera/Azure-Virtual-Machine/assets/89204562/0eda31e7-351d-4bbe-b737-bcab2f0bde90">










