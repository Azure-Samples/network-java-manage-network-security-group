---
page_type: sample
languages: java
products: azure
services: virtual-network
platforms: java
author: yaohaizh
---

## Getting Started with Network - Manage Network Security Group - in Java ##


  Azure Network sample for managing network security groups -
   - Create a network security group for the front end of a subnet
   - Create a network security group for the back end of a subnet
   - Create Linux virtual machines for the front end and back end
   -- Apply network security groups
   - List network security groups
   - Update a network security group.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-network-security-group.git

    cd network-java-manage-network-security-group

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.