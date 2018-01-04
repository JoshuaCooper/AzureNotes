https://docs.microsoft.com/en-us/azure/azure-glossary-cloud-terminology#account

### Azure Glossary of terms

## account
An account that's used to access and manage Azure subscription. It's often referred to as an Azure account although an account can be any of thes: an existing work, school or personal Microsoft account, or an Office 365 user name and password. You can also create an account to manage an Azure subscription when you sign up for the free trial.

## App Server app(API app)
The compute resources that Azure App Service provides for hosting a website or web application, web API, or mobile appbackend. App Service apps are also regerred to as App Services, web apps, API apps, and mobile apps.

## availability set
A collection of virtual machines that are managed together to provide application redundancy and reliability. The use of an availability set ensures that during, either a planned or unplanned maintenance event at least one virtual machine is available. 

## Azure classic deployment model
One of two deployment models used to deploy resources in Azure (the new model is Azure Resouce Manager). Some Azure servies support only the Resource Manager deployment model, some support only the classic deployment model, and some support both. The documentation for each Azure services specifies which model(s) they support.

## fault domain 
The collection of virtual machines is an availability set that can possibly fail at the same time. An example is a group of machines in a rack that share a common power source and network switch. In Azure, the virtual machines in availability set are automatically seperated across multiple fault domains.

## geo 
A defined boundary for data residency that typically contains two or more regions. The boundaries may be within or beyond national borders and are influenced by tas regulation. Every geo has at least one region. Examples of geos are Asia Pacific and Japan. Also called geography.

## geo-replication
The process of automatically replicating content such as blobs, tables and queues within a regional pair.

## image
A file that contains the operating system and application configuration that can be used to create any number of virtual machines. In Azure there are two types of images: VM image and OS image. A VM image includes an operating system and all disks attached to a virtual machine when the image is created. An OS image contains only a generalized operating system with no data disk configurations.

## limits
The number of resources that can be created or the performance benchmark that can be achieved. Limits are typically associated with subscriptions, services, and offerings.

## load balancer
A resource that distributes incoming traffice among computers in a network. In Azure, a load balancer distributes traffice to virtual machines defined in a load-balancer set. A load balancer can be internet-facing, or it can be internal.

## mobile app
Another name for App Service App.

## offer
The pricing, credits, and related terms applicable to an Azure subscription.

## portal
The secure web portal used to deply and manage Azure services.

## region
An area within a geo that does not cross national borders and contains one or more datacenters. Pricing, regional services, and offer types are exposed at the regional level. A region is typically paired with another region, which can be up to several hundred miles away. Regional pairs can be used as a mechnaism for disater recovery and high availability scenarios. Also referred to as a location. 

## resource
An item that is part of your Azure solution. Each Azure service enables you to deploy different types of resources, such as databases or virtual machines.

## resource group
A container in Resource Manager that holds related resources for an application. The resource group can include all of the resources for an application, or only those resources that are logically grouped together. You can decide how you want to allocate resources to resource groups based on what makes the most sense for your organization.

## Resource Manager template
A JSON file that declaratively defines one or more Azure resouces and that defines dependencies between the deployed resources. 

## role 
A means for controllin access that can be assigned to users, groups, and services. Roles are able to perform actions such as create, manage, and read on Azure resources.

## service level agreement (SLA)
The agreement that describes Microsoft's commitments for uptime and connectivity. Each Azure service has a specifi SLA.

## share access signature(SAS)
A signature that enables you to grant limited access to a resource, without exposing your account key. For example, Azure Storage uses SAS to grant client access to objects such as blobls. IoT hub uses SAS to grant devices permission to send telemetry.

## storage account
An account that gives you access to the Azure Blob, Queue, Table, and File services in Azure Storage. The storage account name defines the unique namespace for Azure Storage data objects.

## subscription
A customer's agreement with Microsoft that enables them to obtain Azure services. The subscription pricing and related terms are governed by the offer chosen for the subscription. See Microsoft Online Subscription Agreement and How Azure subscriptions are associated with Azure Active Directory.

## tag
An indexing term that enables you to categorize resrouces according to your requirements for managing or billing. When you have a complex collection of resources, you can use tags to visualize those assets in the way that makes the most sense. For example, you could tag resources that serve a smiliar role in your organization or belong to the same department. 

## update domain
The collection of virtual machines in an availability set that are updated at the same time. Virtual machines in the same update domain are restarted together during planned maintenance. Azure never restarts more than one update domain at a time. Also referred to as an upgrade domain.

## virtual machine 
The software implementation of a physical computer that runs an operating system. Multiple virtual machines can run simutaneously on the same hardware. In Azure, virtual machines are available in a variety 

## virtual machine extension
A resource that implements behaviors of features that either help other programs work or provide the ability for you to interact with a running computer. For example, you could use the VM Access extension to reset or modify remote access values on an Azure virtual machine.

## virtual network
A network that provides connectivity between your Azure resources that is isolated from all other Azure tenants. An Azure VPN Gateway lets you establish connections between virtual networks and between a virtual network and an on-premises network. You can fully control the IP address blocks, DNS settings, security policies, and route tables within a virtual network. 

## Web app
Another name for App Service App.
