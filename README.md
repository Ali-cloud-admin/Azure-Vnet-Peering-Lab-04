**Lab 4: Azure Virtual Network Peering**

**🎯 Objective**
Establish bidirectional peering between two Azure Virtual Networks using PowerShell, verify connectivity, and confirm synchronization in the Azure portal.

**⚙️ Resources Deployed**

Resource Group: rg-vnet-peering-lab

Virtual Network A: vnet-lab-a

Virtual Network B: vnet-lab-b

Peering A → B: vnet-a-to-b

Peering B → A: vnet-b-to-a

**📸 Screenshots**

## Resource Group Creation
**Description:** Shows successful creation of the resource group 'rg-vnet-peering-lab' in East US.
![rg-creation-output.png](rg-creation-output.png)  

## Virtual Network Creation
**Description:** Displays creation of two VNets ('vnet-lab-a` and `vnet-lab-b') with subnets defined.
![vnetA+vnetB-creation.png](vnetA+vnetB-creation.png)  

**Description:** Azure portal view listing both VNets inside the resource group.
![vnet-creation-portal-list.png](vnet-creation-portal-list.png)  

## VNet Peering Setup
**Description:** PowerShell output confirming peering between 'vnet-lab-a' and 'vnet-lab-b'.
![PS-Peering-list.png](PS-Peering-list.png)  

**Description:** Shows bidirectional peering creation with provisioning state succeeded.
![vnet-peering-a-to-b-&-b-to-a.png](vnet-peering-a-to-b-&-b-to-a.png)  

**Description:** Portal view of peering 'vnet-a-to-b' showing status connected and synchronized.
![vnet-a-to-b-portal-list.png](vnet-a-to-b-portal-list.png)  

**Description:** Portal view of peering 'vnet-b-to-a' showing status connected and synchronized.
![peering-vnet-b-to-a-portal-list.png](peering-vnet-b-to-a-portal-list.png)  

## Verification
**Description:** PowerShell verification of peering properties (AllowVirtualNetworkAccess = True).
![PS-Peering-list.png](PS-Peering-list.png)  

**📚 Key Learnings**

How to create and configure Azure Virtual Networks with subnets using PowerShell.
How to establish bidirectional VNet peering with PowerShell.
How to verify peering status both via PowerShell and the Azure portal.
Understanding synchronization and connectivity indicators in Azure portal.

**📌 Resume Bullets**

Provisioned and configured Azure Virtual Networks with subnets using PowerShell.
Established bidirectional VNet peering between two VNets.
Verified peering connectivity and synchronization using PowerShell and Azure portal.
Demonstrated secure and seamless cross-network communication setup in Azure.
