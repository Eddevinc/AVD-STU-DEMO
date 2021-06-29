# **Demo 3: Admin Walk through**


## **Networking and Domain Controllers overview**

In this demo, we will walk through the Azure networking and Domain Controller setup.


**Talk through**   
 - For this Demo, we have deployed two Domain Controllers; one in East US and one in Central US.
 - A VM Running Azure Connect application is Syncing Active Directory with Azure Active Directory

![ws name.](media/img31.png)

- There are 2 vNets deployed in Azure, one in East and one in Central region.

![ws name.](media/img32.png)

- These vNets are connected to each other using vNet Peering.

![ws name.](media/img33.png)

- Both the vNets are configured to use the IP address of the Domain Controllers as DNS Servers.   
   
![ws name.](media/img34.png)