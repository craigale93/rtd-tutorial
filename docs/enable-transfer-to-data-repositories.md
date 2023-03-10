---
title: "Enable Transfer to Data Repositories"
date: "2022-02-23"
---

  
Currently openBIS offers an integration with the **Zenodo** data repository ([https://zenodo.org/).](https://zenodo.org/) 

This enables data direct data transfer from openBIS to Zenodo.

This feature needs to be configured by a _system admin_ as explained here: [openBIS DSS configuration file](https://unlimited.ethz.ch/display/openBISDoc2010/Installation+and+Administrators+Guide+of+the+openBIS+Data+Store+Server#InstallationandAdministratorsGuideoftheopenBISDataStoreServer-Configurationfile). 

If this is done, the Zenodo Export needs to be made visible in the ELN UI by a lab manager, who has should have admin rights for the **Settings**. This can be done by a _group admin_, in case of a multi-group instance set up.

  
Procedure:  
  

1. Edit the **Settings** under **Utilities.**
2. Select **showZenodoExportBuilder** in the **Main Menu** section.
3. **Save.**

![](https://openbis.ch/wp-content/uploads/2020/02/Screenshot-2020-02-26-at-10.53.37-1024x679.png)

The **Export to Zenodo** functionality becomes available under the **Utilities** menu (a refresh of the browser page may be necessary to see the change):

![](https://openbis.ch/wp-content/uploads/2022/02/zenodo-export.png)
