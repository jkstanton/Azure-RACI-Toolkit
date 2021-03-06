# Azure RACI Toolkit

## What is a RACI?
Establishing a good foundation of governance is critical to effectively consuming cloud services. A core component of that governance involves the creation of a Roles Assignment Matrix (RACI). RACI stands for **responsible, accountable, consulted,** and **informed**. The matrix contains a listing of tasks which are assigned to functional roles. For each task there is always one accountable party, one or more responsible parties, and optionally consulted or informed parties. Accountable parties are the decision makers and are accountable for the success or failure of the task. Responsible parties have a responsibility in completing the task but are not accountable for the success or failure of the task. Consulted parties may be consulted during a task for best practices or advice but are not responsible or accountable for the success or failure of the task. Informed parties have an interest in whether or not the task is successful but are not directly involved in completion of the task.

## What is the purpose of this RACI?
The purpose of this RACI is to provide a foundation for organizations beginning the journey into Microsoft Azure. It contains common tasks across both governance and operations that organizations should identify owners and operators for. It is by no means inclusive of all of the tasks required to administer Microsoft Azure and should only be considered a starting point that organizations can draw upon to help accelerate the development of their own robust and detailed RACI. Larger and more complex organizations should expect to spend a few weeks to a month assembling their RACI. 

We start out with seven common functional roles which have broad applicability across both large and small organizations:


| Role          | Description   | 
| ------------- |:-------------|
| **Cloud Service Owner**    | Individual who is accountable for service management for cloud services; cloud architect | 
| **Workload Owner**    | Development team or primary support personnel for workload | 
| **Operations**    | Tier 2 day to day operation of the environment such as troubleshooting and incident management | 
| **Security Auditors**    | Tier 2 team responsible for validating security configuration for compliance | 
| **Systems Operators**     | Tier 3 team responsible for design, implementation, and configuration of compute resources (VMs, SQL, etc)     |   
| **Network Operators** | Tier 3 team responsible for design, implementation, and configuration of network resources (Vnet, routing tables, etc)   |   
| **Security Admins**    | Tier 3 team responsible for setting security policy and configuration of security solutions | 


For each task listed in the RACI Matrix, identify which role(s) above will have ownership either as **responsible** parties, an **accountable** party, a **consulted** party, or  **informed** party. If you need to modify or add an additional role or task, simply add it to the matrix and populate accordingly. The matrix provided is not an exhaustive list of tasks but rather a subset of actions required to establish a minimum viable cloud. This baseline set of actions should provide a good starting point from which you can compose your own cloud operating model, roles and responsibilities.

## What else is in this toolkit?
This toolkit also includes a set of reference worksheets and scripts to assist in the definition and creation of your own custom RBAC role(s).

| Artifact      | Description   | 
| ------------- |:-------------|
| **Built-in RBAC Roles** | Complete list of RBAC roles built-in to Azure|
| **Azure Service Namespaces** | Complete list of Azure Services and their security namespaces| 
| **Service Actions** | All available RBAC actions(non-data) on Azure resources e.g. create virtual machine, read logs|
| **Data Actions** | All available actions on data e.g. read storage blob|
| **Powershell** | Source scripts to refresh data and create/manage custom RBAC roles |


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
