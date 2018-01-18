## Setup
***

The LocalCart scenarios are build on [IBM Cloud services](https://console.bluemix.net/catalog/), the [Watson Data Platform](https://www.ibm.com/analytics/us/en/watson-data-platform/) and third-party cloud storage services.

<img src="https://raw.githubusercontent.com/ibm-watson-data-lab/localcart-at-index-conf/master/images/localcart%20overview.png"></img>


Complete the following steps to get set up for the scenarios.

1. Login to the [Watson Data Platform](https://dataplatform.ibm.com) or sign up.

1. Provision the required Cloud data services
    1. Open the Data Services page
        * Click [this link](https://dataplatform.ibm.com/data/discovery?target=services&context=analytics) or choose **Data Services** > **Services** from the main menu
    1. Provision the following IBM Cloud Services (if you don't already have an instance provisioned)
       * Compose for Redis (Standard plan, which is not free) [[Learn more...]](https://console.bluemix.net/catalog/services/compose-for-redis)
       * Message Hub (Standard plan, which is not free) [[Learn more ...]](https://console.bluemix.net/catalog/services/message-hub)
1. Add the Data Catalog app to your Watson Data Platform
   * Click the avatar icon on the upper right hand side and choose **Add Other Apps**. Skip the next step if this option is not displayed. 
   * Choose the **Data Catalog Lite** plan, which is free. 
1. Create a project  
   * Click [this link](https://dataplatform.ibm.com/projects/new-project?context=analytics) or choose **Projects** > **View All Projects** from the main menu
   * Enter a name and select a Cloud Object Storage and Spark service instance. If no instances are available, add new ones.


### Scenario One: Real-time dashboard - dynamic data analysis and visualization

In the project add a new notebook from URL https://github.ibm.com/ibm-watson-data-lab/index-conference-2018-drafts/blob/master/notebooks/localcart-scenario-one.ipynb


### Scenario Two: Static data analysis using Python, Apache Spark and PixieDust

In the project add a new notebook from URL https://github.ibm.com/ibm-watson-data-lab/index-conference-2018-drafts/blob/master/notebooks/localcart-scenario-two.ipynb

### Scenario Three: Build a product recommendation engine

In the project add a new notebook from URL https://github.ibm.com/ibm-watson-data-lab/index-conference-2018-drafts/blob/master/notebooks/localcart-scenario-three.ipynb

### Scenario Four: Build a revenue dashboard using PixieApps
In the project add a new notebook from URL https://github.ibm.com/ibm-watson-data-lab/index-conference-2018-drafts/blob/master/notebooks/localcart-scenario-four.ipynb