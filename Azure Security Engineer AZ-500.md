# Azure Security Engineer (AZ-500)

AZ-500 Links and Schedule

## Links

### Course Materials

- SkillPipe - <https://www.skillpipe.com>
- Learn on Demand Systems - <https://aka.ms/tsfblabs/>
    - LODS Interface Guide - <https://aka.ms/tsfb123>
- Lab Exercises - [GitHub Step by Step Labs](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/tree/master/Instructions/Labs)
- Lab Files - [ZIP File of Labs & Templates](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/archive/master.zip)

### Azure Tools

- Azure Pricing Calculator - <https://azure.microsoft.com/en-us/pricing/calculator/>

### Azure Documentation

- Azure Architecture Center - <https://docs.microsoft.com/en-us/azure/architecture/>
- Azure ARM Template Reference - <https://docs.microsoft.com/en-us/azure/templates/>
- Azure CLI Reference - <https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest>
- Azure N-Tier Architecture - <https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/n-tier/n-tier-sql-server>

### Post-Course

- Post-Course Takeaways - <https://aka.ms/cptakeaway>

## Schedule

### Day One - Logistics, Introductions, and Identity

#### Morning

- Introductions and Agenda
- Setup your Skillpipe account and redeem courseware code
- Login (or setup) a personal Microsoft account
- Connect to lab environment and redeem training key
- Redeem Azure Pass using your personal Microsoft Account

##### Introduction

- Azure Regions - <https://azure.microsoft.com/en-us/global-infrastructure/regions/>
- Azure Region Pairs - <https://docs.microsoft.com/en-us/azure/best-practices-availability-paired-regions>
- Azure Subscriptions - <https://docs.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview>
- Azure Management Groups - <https://docs.microsoft.com/en-us/azure/governance/management-groups/>
- Azure Resource Groups - <https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal>
- Azure Portal Demo

##### Manage Identity and Access

- Identity Management
    - Azure Active Directory [Docs](https://docs.microsoft.com/en-us/azure/active-directory/)
- Hybrid Identity
    - Azure AD Connect [Docs](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-azure-ad-connect)
    - Password Hash Synchronization / Password writeback
    - Pass-through Authentication
    - [Decision Tree](https://github.com/Azure/fta-identity/blob/master/identity-applications/aad-external-identities-decision-tree.md)
- Risk Policies [Docs](https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/concept-identity-protection-policies#user-risk-policy)
- Conditional Access [Docs](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/overview)


#### Afternoon

- Governance
    - Azure AD Roles [Docs](https://docs.microsoft.com/en-us/azure/role-based-access-control/rbac-and-directory-admin-roles)
    - Azure RM Roles
    - Custom Roles
    - Management Groups [Docs](https://docs.microsoft.com/en-us/azure/governance/management-groups/)
    - Azure Policy [Docs](https://docs.microsoft.com/azure/azure-policy)
    - Resource Locks [Docs](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-lock-resources)

- Labs
    - [Role-based Access Control](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_01_RBAC.md)
    - [Azure Policy](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_02_AzurePolicy.md)
    - [Resource Locks](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_03_AzureLocks.md)
    - [Multi-Factor Authentication](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_04_MFAConditionalAccessandAADIdentityProtection.md)
   
### Day Two - Platform Security

#### Morning

- Privileged Identity Management [Docs](https://docs.microsoft.com/en-us/azure/active-directory/privileged-identity-management/pim-configure)
    - Time-bound access
    - Approvals and justifications

- Perimeter Security
    - Virtual Network Security
    - DDoS Protection [Docs](https://docs.microsoft.com/en-us/azure/virtual-network/ddos-protection-overview)
    - Azure Firewall [Docs](https://docs.microsoft.com/en-us/azure/firewall/overview)
    - VPN Gateways w/ Tunneling [Docs](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-forced-tunneling-rm)
    - User Defined Routes [Docs](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-udr-overview)

- Labs
    - [Privileged Identity Management](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_05_PIM.md)
    - [Identity Synchronization](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_06_ImplementDirectorySynchronization.md)
    


#### Afternoon

- Network Connectivity
    - Network Security Groups [Docs](https://docs.microsoft.com/en-us/azure/virtual-network/security-overview#network-security-groups )
    - App Security Groups
    - Service and Private Endpoints [Docs](https://docs.microsoft.com/en-us/azure/private-link/private-link-overview)
    - Azure App Gateway / Web App Firewall [Docs](https://docs.microsoft.com/en-us/azure/application-gateway)
    - Azure Front Door / Traffic Manager [Docs](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-overview)
    - ExpressRoute [Docs](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-introduction)

 
 - Labs
    - [Network Security Groups](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_07_NSGs.md) 
    - [Azure Firewall](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_08_AzureFirewall.md)

### Day Three - Data and App Security

#### Morning

- Host Security
    - Endpoint Protection
    - Privileged Access Workstations
    - VM Templates [Docs](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
    - Remote Access Management - Azure Bastion [Docs](https://docs.microsoft.com/en-us/azure/bastion/bastion-overview)
    - Update management
    - Disk encryption [Docs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-overview)
    - Security Center [Docs](https://docs.microsoft.com/en-us/azure/security-center/security-center-virtual-machine-protection)
    
- Container Security
    - Azure Container Registry [Docs](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro)
    - Azure Container Instances [Docs](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview)
    - Azure Kubernetes Service [Docs](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)
    
- Azure Key Vault [Docs](https://docs.microsoft.com/en-us/azure/key-vault/general/overview)
    - Keys
    - Certificates
    - Secrets

- Lab
    - [Key Vault](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_10_KeyVaultImplementingSecureDatabysettingupAlwaysEncrypted.md)
    - [Container Security](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_09_ConfiguringandSecuringACRandAKS.MD)

#### Afternoon

- Application Security
    - App Registration [Docs](https://docs.microsoft.com/en-us/graph/auth/auth-concepts#register-your-app-with-the-microsoft-identity-platform)
    - Web App Certificates [Docs](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-configure-tls-mutual-auth)
- Storage Security
    - Storage Accounts
    - Shared Access Signatures [Docs](https://docs.microsoft.com/en-us/rest/api/storageservices/delegate-access-with-shared-access-signature)
    - Storage Encryption [Docs](https://docs.microsoft.com/en-us/azure/storage/common/storage-service-encryption)
    - Retention policies [Docs](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-immutability-policies-manage?tabs=azure-portal)
- Database Security
    - SQL Authentication [Docs]( https://docs.microsoft.com/en-us/azure/sql-database/sql-database-manage-logins)
    - Database Firewalls [Docs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-firewall-configure)
    - Database auditing [Docs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-auditing)
    - Data discovery and classification [Docs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-data-discovery-and-classification)
    - Dynamic Data Masking [Docs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-dynamic-data-masking-get-started)
    - Transparent Data Encryption [Docs](https://docs.microsoft.com/en-us/azure/sql-database/transparent-data-encryption-azure-sql?tabs=azure-portal)
    - Always Encrypted [Docs](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine?view=sql-server-ver15)
- Labs
    - [Securing SQL Databases](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_11_SecuringAzureSQLDatabase.MD)
    - [Securing Storage](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_12_SecuringAzureStorage.MD)

### Day Four - Security Operations

#### Morning

- Azure Monitor
    - Metrics and Alerts [Docs](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform-metrics)
    - Log Analytics [Docs](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-create-workspace)
- Security Center [Docs](https://docs.microsoft.com/en-us/azure/security-center)
    - Policies
    - Secure Score
    - Compliance
- Azure Sentinel [Docs](https://docs.microsoft.com/en-us/azure/sentinel/overview)
    - Data Connections
    - Workbooks
    - Incidents
    - Playbooks
    - Hunting
- Wrapup
    - Survey
    - [Takeaways review](https://aka.ms/cptakeaway)
    - Additional learning options
    - Learner Experience Portal review [LxP](https://esi.microsoft.com)
    
#### Afternoon


- Labs
    - [Azure Monitor](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_13_Azure%20Monitor.md)
    - [Security Center](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_14_Security%20Center.md)
    - [Azure Sentinel](https://github.com/MicrosoftLearning/AZ500-AzureSecurityTechnologies/blob/master/Instructions/Labs/LAB_15_Azure%20Sentinel.md)
