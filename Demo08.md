# AVD Management with Intune

## Microsoft Intune

Microsoft Intune is a cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM). You have control over how your organization's 
devices, including corporate devices, mobile phones, tablets, and laptops, are utilised. You can also define particular security policies to control applications. 

Intune integrates with Azure Active Directory (Azure AD) to control who has access and what they can access. It also works with Azure Information Protection to protect data. It is compatible with the Microsoft 365 range of products.

For example, you can deploy Microsoft Teams, OneNote, and other Microsoft 365 apps to devices. This feature helps employees in your organization to be productive across all of their devices while also protecting your organization's data through regulations you define.


## Microsoft Endpoint Manager

Microsoft Intune has moved to Microsoft Endpoint Manager. It contributes to the delivery of a modern workplace and modern management in order to keep your data protected whether in the cloud and on-premises. 
Endpoint Manager provides services and tools for managing and monitoring mobile devices, desktop computers, virtual machines, embedded devices, and servers.

It combines services including Microsoft Intune, Configuration Manager, Desktop Analytics, co-management, and Windows Autopilot and much more.


## AVD Management with Intune

Following are the technical configurations and criteria that must be completed before we can use WVD Intune.

* Make sure the VMs are Hybrid AAD Join - Azure AD Connect confirgutation should be in place to support Hybrid Azure AD Join scenarios.
* MDM Group Policy for All WVD VMs - This is a way to enroll Hybrid Azure AD joined Windows devices to Intune automatically. 

Now we will move to Microsoft Endpoint Manager.

1. Open a browser and sign in to the [Microsoft Endpoint Manager admin center](https://go.microsoft.com/fwlink/?linkid=2109431).

2. When you open the Microsoft Endpoint Manager, the service is displayed in a pane of your browser. Some of the first workloads you may use in Intune include Devices, Apps, Users, and Groups. A workload is simply a sub-area of a service. When you select the workload, it opens that pane as a full page. Other panes slide out from the right side of the pane when they open, and close to reveal the previous pane.

By default, when you open the Microsoft Endpoint Manager you'll see the Home page pane. This pane provides an overall visual snapshot of tenant status and compliance status, as well as other helpful related links

![ws name.](media/demo08-08.png)





