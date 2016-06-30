---
services: networking
platforms: java
author: selvasingh
---

#Getting Started with Network - Manage Network Security Group - in Java #

Networking Manage Network Security Group Sample (for 1.0.0-beta2) - demonstrates how to perform common management tasks using the Microsoft Azure Networking service.


- Create a network security group for the front end of a subnet
- Create a network security group for the back end of a subnet
- Create Linux virtual machines for the front end and back end
	- Apply network security groups
- List network security groups
- Update a network security group.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-network-security-group.git

    cd network-java-manage-network-security-group

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

[Azure Networking](https://azure.microsoft.com/en-us/services/virtual-network/)

[Azure Network Security Group](https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-nsg/)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.