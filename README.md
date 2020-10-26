---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Monitor
  platforms: java
---

# Getting Started with Monitor - Web App Performance Monitoring Alerts - in Java #


  This sample shows examples of configuring Metric Alerts for WebApp instance performance monitoring through app service plan.
   - Create a App Service plan
   - Setup an action group to trigger a notification to the heavy performance alerts
   - Create auto-mitigated metric alerts for the App Service plan when
     - average CPUPercentage on any of Web App instance (where Instance = ) over the last 5 minutes is above 80%
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/monitor-java-metric-alerts-on-critical-performance.git

    cd monitor-java-metric-alerts-on-critical-performance

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.