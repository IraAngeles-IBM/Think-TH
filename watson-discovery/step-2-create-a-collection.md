---
description: Your first step in the Discovery tooling is to create a data collection.
---

# Step 2: Create a collection

A collection is a set of your documents. _Why would I want more than one collection?_ There are a few reasons:

* You might want multiple collections in order to separate results for different audiences.
* The data might be so different that it doesn't make sense for it all to be queried at the same time.

The public, pre-enriched Discovery News data collection is also available for your use. It is ready to query, and you can begin to create queries on it immediately. You cannot adjust its configuration or add documents to Discovery News.

1. Click ![Environment details](https://cloud.ibm.com/docs-content/v1/content/services/discovery/images/env_icon.png?locale=en) and choose **Create environment**.
2. When your environment is ready, click the **Upload your own data** button, then you can **Name your new collection**. Name your collection **InstallDocs**.

   When creating a collection, under **Advanced**, you have the option to choose a configuration file named **Default Contract Configuration**. This configuration supports only the Element Classification enrichment, which can be used to extract party, nature, and category from elements in PDFs. See [Element Classification](https://cloud.ibm.com/docs/services/discovery?topic=discovery-element-classification&locale=en-US#element-collection) for details. Do not choose this option for this tutorial.

