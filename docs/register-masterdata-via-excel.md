---
title: "Register masterdata via Excel"
date: "2022-02-23"
---

 

It is possible to register openBIS masterdata using an Excel template from the admin UI.

 

This can be done from the Import menu under the Tools sections, as shown below. Three options can be chosen for the import:

 

1. **fail if exists**: if a type or a property already exists in the database, the upload will fail.
2. **ignore if exists**: if a type or a property already exists in the database, the upload will ignore this.
3. **update is exists**: if a type or a property already exists in the database, the upload will update existing values.

 

![](https://openbis.ch/wp-content/uploads/2022/02/Excel-import-admin-UI-1024x634.png)

 

 

An example template of an Excel masterdata file can be found here: [masterdata-template](https://openbis.ch/wp-content/uploads/2022/02/masterdata-template.xls)

Please note that in the template we used separate spreadsheets for each type (Sample, Experiment, Dataset), but it is also possible to have everything in one single spreadsheet.

 

## Modifying existing types

If you wish to add a new property to an existing _Collection/Object/Dataset_ type, you need to:

1\. add the property in the file

2\. increase the version number of the _Collection/Object/Dataset_ type

 

![](https://openbis.ch/wp-content/uploads/2022/02/masterdata-type-version.png)

3\. use **Ignore if exists** as upload method. In this case, only the new property is added to the type.

 

The import on the admin UI allows to register entities in addition to masterdata. An example template file for this can be found here: [masterdata-metadata](https://openbis.ch/wp-content/uploads/2022/02/masterdata-metadata.xls)

 

More extensive documentation on the XLS format for masterdata and metadata registration can be found [here](https://unlimited.ethz.ch/display/openBISDoc2010/Excel+Import+Service).
