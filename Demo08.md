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

2. The Home page pane provides an overall visual snapshot of **Tenant status** and **Compliance status**, as well as other helpful related links. 

![ws name.](media/demo8-08.png)

3. In the Microsoft Endpoint Manager, you will have all the services displayed in a pane on the left side of the browser. 

![ws name.](media/demo8-09.png)

4. Select **Dashboard** from the navigation pane. It displays overall details about the devices and client apps in your Intune tenant.

![ws name.](media/demo08-10.png)

5. Now move to **Devices** available under _Favorites_ tab. This section display the details about the enrolled devices in your Intune tenant.

![ws name.](media/demo08-11.png)

6. On the **Overview** page, the strip on the top have several tabs that allow you to view a summary of the following statuses and alerts:

* **Enrollment status -** Here you will have details about the devices enrolled with Intune by platform and enrollment failures.

![ws name.](media/demo08-12.png)

* **Enrollment alerts -** One can find more details about the devices those are unassigned by the platform.
 
![ws name.](media/demo08-13.png)

* **Compliance status -** This section displays a list of devices that do not have a compliance policy. Also you can review the status of compliance in terms of device, policy, setting, threats, and protection.

![ws name.](media/demo08-14.png)

* **Configuration status -** Here you can review the configuration status of device profiles as well as profile deployment.

![ws name.](media/demo08-15.png)

* **Software update status -** In this section, one can have a look to visuals of the deployment status for all devices and for all users.

![ws name.](media/demo08-16.png)











