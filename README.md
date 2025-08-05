# AZ-900.

This repository documents my hands-on lab work while preparing for the Microsoft Certified: Azure Fundamentals (AZ-900) exam. These labs provide foundational experience across core Azure services and concepts.

## ✅ Learning Objectives
**🌐 Networking & Compute**
- Explore and create Azure Virtual Networks
- Understand and implement network security and traffic management
- Deploy Virtual Machines using:
- Azure Portal
- ARM Templates
- PowerShell
- Azure CLI

## 💾 Storage & Databases
- Explore Azure Storage services and create Blob storage
- Understand Azure SQL Database and deploy an instance
- Implement basic storage security and access control

## 🛠️ App Services & Serverless
- Deploy and manage an Azure Web App
- Implement Azure Functions for event-driven workloads
- Explore services in the Azure Marketplace

## 🛰️ IoT & AI
- Define Azure IoT concepts and implement IoT Hub
- Explore Azure AI services and integration possibilities

## 🔐 Security, Identity & Governance
- Understand Azure Identity Services (Azure AD, RBAC)
- Implement:
- Azure Security Center
- Azure Key Vault
- Azure Policy
- Azure Resource Locks
- Azure Blueprints
- Resource Tagging

## 📊 Monitoring & Compliance
- Use Azure Monitor for resource tracking and diagnostics
- Explore Privacy, Compliance, and Trust Center
- Navigate the Service Trust Portal (STP)

## 💸 Cost Management & Support
Learn to use:
- Azure Pricing Calculator
- Total Cost of Ownership (TCO) Calculator
- Cost Management tools
- Understand Azure Subscriptions, SLAs, and support tiers

<details>
<summary><b>Creating Azure Virtual Machine Via Azure Portal</b></summary>

## STEP-BY-STEP

1. **Sign in to Azure Portal**
   - https://portal.azure.com
2. **Search for "Virtual Machines"**
   - In the top search bar, type and select Virtual Machines.
3. **Click “Create” > “Azure virtual machine”**
4.  ## Configure Basics
   - Subscription: Select your Azure subscription
   - Resource Group: Create a new one or use existing
   - Virtual machine name: e.g., myVM
   - Region: Choose your preferred Azure region
   - Availability options: Leave default unless high availability is needed
   - Image: Choose OS (e.g., Ubuntu 20.04 LTS or Windows Server 2022)
   - Size: Select based on your use (e.g., Standard_B1s for testing)
   - Authentication type:
     - SSH public key for Linux
     - Password for Windows
   - Username: e.g., azureuser
   - SSH key: Generate or paste your public key (for Linux)
     
  <img width="1875" height="905" alt="Screenshot 2025-08-04 at 4 15 50 PM" src="https://github.com/user-attachments/assets/fd7e54ff-1c0e-401c-a71a-a4355b63dce4" />


5. ## Configure Inbound Ports
   - Select SSH (22) for Linux or RDP (3389) for Windows
   - Add HTTP (80) if running a web server

6. ## Click Next through remaining tabs (Disks, Networking, etc.)
   - You can leave most settings as default for basic deployment.

7. ## Click “Review + create” > “Create”
8. ## Deployment will take a few minutes, then click “Go to resource”

  <img width="1311" height="919" alt="Screenshot 2025-08-04 at 4 18 12 PM" src="https://github.com/user-attachments/assets/98c5554b-6d64-47c7-80be-41cf6f5d519e" />


</details>

<details>
<summary><b>How To Create A Web Server On Azure VM Via Powershell</b></summary>

1. ## Run Powershell as Administrator on your VM
2. ## Run the command "Install-WindowsFeature -name Web-Server -IncludeManagementTools

<img width="625" height="186" alt="Screenshot 2025-08-05 at 11 42 39 AM" src="https://github.com/user-attachments/assets/6a1d1fbe-feef-41ed-ae7f-37a0c30c8ccc" />

<img width="487" height="127" alt="Screenshot 2025-08-05 at 11 44 33 AM" src="https://github.com/user-attachments/assets/3503f198-26e7-4d74-9e15-4f41bf826b9e" />



   
</details>

