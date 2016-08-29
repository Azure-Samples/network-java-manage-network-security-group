---
services: networking
platforms: java
author: selvasingh
---

# Getting Started with Networking in Java: Manage Network Security Group

This sample shows how to use Java to manage a network security group for your Microsoft Azure network.

The sample performs these tasks:

- Create a network security group for the front end of a subnet
- Create a network security group for the back end of a subnet
- Create Linux virtual machines for the front end and back end
	- Apply network security groups
- List network security groups
- Update a network security group.
 

## Running this Sample ##

To run this sample:

1. If you don't already have a Microsoft Azure subscription, you can register for a [free trial account](http://go.microsoft.com/fwlink/?LinkId=330212).

2. Install the [Azure Management Libraries for Java](https://github.com/Azure/azure-sdk-for-java/). These libraries contain the Azure Storage Resource Provider.

3. Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md) for more information.

4. Clone this repository: 

	    git clone https://github.com/Azure-Samples/network-java-manage-network-security-group.git

5. Navigate to the source directory for the sample:

	    cd network-java-manage-network-security-group

6. Build the project with [Maven](https://maven.apache.org/download.cgi):

	    mvn clean compile exec:java


## More information ##

- [Microsoft Azure Java developer center](https://azure.microsoft.com/en-us/develop/java/)
- [Azure Networking](https://azure.microsoft.com/services/virtual-network/)
- [Azure Network Security Group](https://azure.microsoft.com/documentation/articles/virtual-networks-nsg/)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.