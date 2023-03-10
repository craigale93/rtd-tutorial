---
title: "Batch update entries in several Collections"
date: "2022-03-04"
---

 

It is possible to batch update _Objects_ that belong to different _Collections_.

This can be done from the **Object Browser** page, under **Utilities**. Two options are available:

 

1. **XLS Batch Update Objects**: batch update via Excel template file.
2. **Batch Update Objects**: batch update via .tsv template file.

 

![](https://openbis.ch/wp-content/uploads/2022/03/object-browser.png)

## XLS Batch Update Objects

This option for batch update is available since openBIS version 20.10.3. It allows to update _Objects_ of different types that belong to different _Collections_.

You can select which types you want to update from the list of available types.

![](https://openbis.ch/wp-content/uploads/2022/03/object-browser-xls-batch-update.png)

 

You can then download the template that will allow you to update _Objects_ of the selected types to single or multiple _Collections_. The _Space, Project, Collection_ need to be entered in the file. The complete path for _Projects_ and _Collections_ need to be used. In addition, identifiers for the _Objects_ need to be provided: identifiers are unique in openBIS, by providing them openBIS will know which _Objects_ have to be updated. Example file: [SAMPLE-GENERAL-REGISTRATION-EXPERIMENTAL\_STEP-MASS\_MEASUREMENT-SAMPLE-template](https://openbis.ch/wp-content/uploads/2022/03/SAMPLE-GENERAL-REGISTRATION-EXPERIMENTAL_STEP-MASS_MEASUREMENT-SAMPLE-template-1.xlsx)

 

 

## Batch Update Objects

 

The batch update via .tsv file allows to batch update only one type of _Object_ at a time. However, it is possible to update _Objects_ that belong to several _Collections_.

This batch update method is kept for backward compatibility, but it will be phased out.

 

![](https://openbis.ch/wp-content/uploads/2022/03/object-browser-batch-update.png)

 

The _Space, Project, Collection_ need to be entered in the file. The complete path for _Projects_ and _Collections_ need to be used. In addition, identifiers for the _Objects_ need to be provided: identifiers are unique in openBIS, by providing them openBIS will know which _Objects_ have to be updated.

 

![](https://openbis.ch/wp-content/uploads/2022/03/Screenshot-tsv-file-batch-upload-1024x221.png)
