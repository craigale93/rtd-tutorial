---
title: "Export to Zenodo"
date: "2022-03-04"
---

  
Currently openBIS offers an integration with the **Zenodo** data repository ([https://zenodo.org/).](https://zenodo.org/)

  
This enables data direct data transfer from openBIS to Zenodo. First of all the connection to Zenodo needs to be configured by a _system admin_ in the DSS service.properties (see [How to configure the openBIS DSS)](https://unlimited.ethz.ch/display/openBISDoc2010/Installation+and+Administrators+Guide+of+the+openBIS+Data+Store+Server) If this is configured, a lab manager, who has admin rights for the **Settings,** needs to enable it in the ELN, as explained in [Enable Transfer to Data Repositories](https://openbis.ch/index.php/docs/admin-documentation-openbis-19-06-4/enable-transfer-to-data-repositories/)**.**

##   
Create Zenodo Personal Access Token

  
In order to be able to export data to Zenodo, you need a valid Zenodo account. You also need to create a **personal access token.** This can be done from the **Applications** under **Settings** in Zenodo, as shown below:

![](images/generate-zenodo-token-1024x498.png)

## Save Zenodo Personal Access Token in openBIS

  
After creating the personal access token in Zenodo, this needs to be stored in openBIS, with the following procedure:

1. Go to **User Profile** under **Utilities** in the main menu.
2. Enable editing.
3. Add the personal access token from Zenodo.
4. **Save.**

![](images/Screenshot-2020-02-27-at-12.50.46.png)

## Export data to Zenodo

  
To export data to Zenodo:

1. Go to **Exports** -> **Export to Zenodo** under **Utilities** in the main menu.
2. Select the data you want to export from the menu.
3. enter a **Submission** **Title.**
4. Click **Export Selected** on top of the export form.
5. You are now redirected to Zenodo, where you should fill in additional metadata information.
6. Publish the entry in Zenodo.
7. After you hit the **Publish** button in Zenodo, a new entry with the details of this submission will be created in the **Publications** folder in the **Inventory**. Please note that this may take a few minutes.

![](images/Screenshot-2020-03-09-at-12.12.10.png)
