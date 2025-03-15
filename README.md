# Azure Basics: Storage Account Implementation

## Project Overview
This project demonstrates fundamental Azure concepts by creating an Azure storage account, managing blob storage, and performing basic file operations. It covers resource group management, Azure portal navigation, and best practices for resource cleanup.

## Environments and Technologies Used
- Microsoft Azure
- Azure Storage
- Azure Blob Storage
- Windows 10 (client system)

## Prerequisites
- Azure subscription (free or paid)
- Basic understanding of cloud computing concepts

## Implementation Steps

### Part 1: Azure Account Setup

#### 1. Azure Subscription Creation
- Created a free Azure subscription at https://azure.microsoft.com/en-us/free/
- Alternatively, a Pay-As-You-Go subscription can be used

![Azure Subscription](https://i.imgur.com/ZUL3S4g.png)

#### 2. Azure Portal Access
- Logged into the Azure Portal at https://portal.azure.com
- Explored the portal layout and key components

![Azure Portal](https://i.imgur.com/RXQmdF4.png)

#### 3. Portal Navigation
- Observed various Azure services:
  - Resource Groups
  - Virtual Machines
  - Entra ID (formerly Azure Active Directory)
- Became familiar with the search bar, notifications, and settings

![Portal Navigation](https://i.imgur.com/6pUCytZ.png)

### Part 2: Resource Group Creation

#### 1. Create Resource Group
- Selected "Resource Groups" from the Azure Portal
- Clicked "Create" to make a new Resource Group
- Named the group "RG-Storage-Demo"
- Selected an appropriate region (e.g., East US)
- Added tags for better organization (optional)
- Completed validation and created the resource group

![Resource Group Creation](https://i.imgur.com/JYAejpw.png)

### Part 3: Storage Account Setup

#### 1. Create Storage Account
- Selected "Storage accounts" from the Azure Portal
- Clicked "Create" to create a new storage account
- Configured basic settings:
  - Selected "RG-Storage-Demo" resource group
  - Named the storage account (must be globally unique)
  - Chose "Standard" performance and "LRS" redundancy for cost efficiency
- Reviewed settings and created the storage account

![Storage Account Creation](https://i.imgur.com/wEuP2IB.png)

#### 2. Storage Account Access
- Navigated to the newly created storage account
- Explored the storage account dashboard
- Located the "Containers" section under "Data storage"

![Storage Account Overview](https://i.imgur.com/X3JWvmN.png)

### Part 4: Blob Storage Operations

#### 1. Create a Text File Locally
- Created a simple text file on local desktop
- For Mac users, ensured it was saved as plain text
- Added some sample content to the file

![Local Text File](https://i.imgur.com/XpSHC1Z.png)

#### 2. Create a Blob Container
- In the storage account, navigated to "Containers"
- Created a new container named "demo-container"
- Set public access level to "Private"

![Create Container](https://i.imgur.com/B2dAD7M.png)

#### 3. Upload the Text File
- Selected the newly created container
- Clicked "Upload" to upload the text file
- Selected the local text file and uploaded it to Azure

![Upload File](https://i.imgur.com/ZcRwLJj.png)

#### 4. Edit File in Azure
- Selected the uploaded text file
- Used the "Edit" feature to modify the file directly in Azure
- Made some changes to the text content
- Saved the changes

![Edit File](https://i.imgur.com/CtD1eSm.png)

#### 5. Download the Modified File
- Selected the file and clicked "Download"
- Saved it to a new location on the local system
- Opened the downloaded file and verified the changes

![Download File](https://i.imgur.com/WtZyRHZ.png)

### Part 5: Resource Cleanup

#### 1. Delete the Resource Group
- Navigated to "Resource Groups" in the Azure Portal
- Located the "RG-Storage-Demo" resource group
- Selected the resource group and clicked "Delete"
- Confirmed deletion by typing the resource group name
- Clicked "Delete" to remove all resources in the group

![Delete Resource Group](https://i.imgur.com/YXqRCnz.png)

#### 2. Verify Deletion
- Refreshed the Resource Groups list
- Confirmed the resource group was no longer listed
- Ensured all associated resources were removed

![Verify Deletion](https://i.imgur.com/KG5L6n0.png)

#### 3. Check Cost Management
- Navigated to "Cost Management + Billing"
- Selected "Cost Analysis"
- Verified no unexpected costs were incurred
- Reviewed resources that might still be generating costs

![Cost Management](https://i.imgur.com/nXf6Z7A.png)

## Lessons Learned
- Creating and managing Azure resources through the Azure Portal
- Understanding resource groups as logical containers for related resources
- Working with Azure Storage accounts and blob containers
- Performing basic file operations in Azure Blob Storage
- Importance of proper resource cleanup to avoid unnecessary costs
- Monitoring Azure costs through Cost Management tools
