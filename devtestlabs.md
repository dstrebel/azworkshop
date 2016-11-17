# Creating Dev\Test Labs

This lab will walk you through creating an Azure Virtual Network.
Azure DevTest Labs is a service that helps developers and testers
quickly create environments in Azure while minimizing waste and controlling cost.
You can test the latest version of your application by quickly provisioning Windows and Linux environments using reusable templates and artifacts.

## 1. Start
* On the left hand side of the Azure portal click "+New"
* Click "Developer Tools" and then Click "DevTest Labs"

![](media/dtl_create.png)

* Enter Lab Name, Subscription, and Location

![](media/dtl_prop.png)

## 2. Modify Policy Settings

#### The folowing policies can be modified:
* Allowed Virtual Machines Sizes
* Virtual Machines per User
* Virtual Machines per Lab
* Auto-Shutdown and Auto-Start

![](media/dtl_policy.png)

## Modify Allowed Virtual Machine Sizes
* Select "Allowed Virtual machine sizes"
* Click Enabled "On"
* Limit to only "Standard A Series"
* Click Save

![](media/dtl_sizes.png)

## 3. Create Virtual Machine

* Select "Overview"
* Click "Add"

![](media/dtl_vm_create.png)

* Select "CentOS 7.2"

![](media/dtl_linux.png)

* Fill in properties

![](media/dtl_vm_prop.png)