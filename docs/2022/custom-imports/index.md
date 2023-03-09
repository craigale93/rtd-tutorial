---
title: "Custom Imports"
date: "2022-08-02"
---

 

From openBIS version 20.10.4, Custom Imports, previously available only in the core UI, are available in the ELN UI.

 

Custom imports allow users to import metadata in a custom way, by using a dropbox script in the background. You can use this if you want to parse a file in a given format and import the information from this file as metadata in openBIS.

 

Custom imports are not available by default, but need to be enabled on the server side by a _system admin_, and a dropbox script needs to be associated with an import (see [Custom Imports](https://unlimited.ethz.ch/display/openBISDoc2010/Custom+Import)).

 

If one or more custom imports are configured in openBIS, the **Custom Import** option is available under the **Utilities** in the **main menu**.

The available custom imports can be selected from the **Custom Import Service** drop down menu in the Custom Import page (see below)

![](images/custom-import-1024x554.png)

 

 

If the available custom import provides a template that can be used as input for the import, the template will be available to download from the Custom Import page.

 

![](images/custom-import-template.png)

 

If the custom import is not configured to provide a template, no download link is shown in the Custom Import page.

 

![](images/custom-import-no-template.png)
