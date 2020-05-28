# Azure Security Engineer (AZ-500)

AZ-500 Links and Schedule

## Links

### Course Materials

- SkillPipe - <https://www.skillpipe.com>
- Learn on Demand Systems - <https://aka.ms/tsfblabs/>
- Lab Exercises - <https://aka.ms/az500labs>
- Lab Files - <https://aka.ms/az500labfiles>

### Azure Tools

- Azure Pricing Calculator - <https://azure.microsoft.com/en-us/pricing/calculator/>

### Azure Documentation

- Azure Architecture Center - <https://docs.microsoft.com/en-us/azure/architecture/>
- Azure ARM Template Reference - <https://docs.microsoft.com/en-us/azure/templates/>
- Azure CLI Reference - <https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest>
- Azure N-Tier Architecture - <https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/n-tier/n-tier-sql-server>

### Azure Serverless

- Create Your First Azure Function - <https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-function-vs-code?pivots=programming-language-csharp>
- Create a Function that Integrates with Logic Apps - <https://docs.microsoft.com/en-us/azure/azure-functions/functions-twitter-email>

### Post-Course

- Post-Course Takeaways - <https://aka.ms/cptakeaway>

## Schedule

### Monday 

#### Logistics
- Introductions and Agenda
- Setup your Skillpipe account and redeem courseware code
- Login (or setup) a personal Microsoft account
- Connect to lab environment and redeem training key
- Redeem Azure Pass using your personal Microsoft Account

#### Introduction

- Azure Regions - <https://azure.microsoft.com/en-us/global-infrastructure/regions/>
- Azure Region Pairs - <https://docs.microsoft.com/en-us/azure/best-practices-availability-paired-regions>
- Azure Availability Sets - <https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability>
- Azure Availability Zones - <https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability>
- Azure Portal Demo

#### Manage Identity and Access

- AAD: Identity Protection
- AAD: Conditional Access (Policies)
- AAD: Conditional Access (Named Locations)
- AAD: Conditional Access (Use Case)
- AAD: Access Reviews
- AAD: Privileged Identity Management
- PIM: Azure AD Roles
- PIM: Settings
- PIM: Azure Resources
- AAD: App Registrations
- AAD: Hybrid Identity
- Subscription Security
- LAB: [Privileged Identity Management](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_1/LAB_01_PIM.md "Lab instructions")

### Tuesday 

#### Platform Security

- Virtual Network Connectivity
- Network Security Groups (NSG): Introduction
- Network Security Groups (NSG): Inbound
- Network Security Groups (NSG): Outbound
- Application Security Groups (ASG)
- Remote Access Management
- Azure Firewall
- Azure Front Door
- LAB: [NSG & ASG](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_2/LAB_05_NSGs.md "Lab instructions")
- LAB: [Azure Firewall](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_2/LAB_12_Azure%20Firewall.md "Lab instructions")

- Virtual Machine Security
    - Antimalware
    - Azure Disk Encryption (ADE)
- Container Security: Azure Kubernetes Service (AKS)
- Container Security: Azure Container Registry (ACR)
- Container Security: AKS & ACR
- Container Networking (CNI)
- Image Security (Content Trust)
- Resource Security: Locks
- Resource Security: Azure Policy
- Resource Security: Role-based Access Control
- Resource Security: Custom Roles
- LAB: [Azure Policy](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_1/LAB_07_Azure_Policy.md "Lab instructions")
- LAB: [Azure Kubernetes Service](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_2/LAB_03_Create%20a%20Kubernetes%20Cluster.md "Lab instructions")

### Wednesday 

#### Securing Data and Applications

- Azure Key Vault: Introduction
- AKV: Access Policies
- AKV: Secrets
- Azure Storage: Public Access Levels
- Azure Storage: Shared Access Signatures
- Azure Storage: Stored Access Policy
- Azure Storage: Encryption
- Azure Storage: Key rotation
- Azure SQL: Introduction
- Azure SQL: Enabled AAD Authentication
- Azure SQL: Auditing
- Azure SQL: Advanced Data Security (ADS)
    - Discovery & Classification
- Azure SQL: Advanced Data Security (ADS) cont'd
    - Vulnerability Assessment
    - Advanced Threat Protection (ATP)
- Azure SQL: Dynamic Data Masking (DDM)
- Azure SQL: Encryption (Always Encrypted)
- Azure SQL: Diagnostics
- LAB: [Implementing Always Encrypted using Key Vault](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_1/LAB_02_Key_Vault.md "Lab instructions")


### Thursday 

#### Security Operations

- Azure Monitor
- Azure Log Analytics
- Diagnostic Logging
- Azure Security Center: Introduction
- ASC: Policy & Compliance
- ASC: Resource Security Hygiene
- ASC: Advanced Cloud Defense
- LAB: [Azure Monitor](https://github.com/MicrosoftLearning/AZ-500-Azure-Security/blob/master/Instructions/Labs/Module_4/LAB_01_Azure%20Monitor.md "Lab instructions")

- Azure Sentinel: Introduction
- Azure Sentinel: Data Connectors
- Azure Sentinel: Workbooks & Incidents
- Azure Sentinel: Hunting & Notebooks
- Azure Sentinel: Analytics
- Azure Sentinel: Playbooks
- Takeaways and closing