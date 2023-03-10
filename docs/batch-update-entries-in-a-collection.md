---
title: "Batch update entries in a Collection"
date: "2022-03-04"
---

It is possible to modify the values of one or more fields in several objects simultaneously via batch update. This can be done in two ways:

1. **XLS Batch Update Objects**
2. **Batch Update Objects**

## XLS Batch Update Objects

1. Navigate to the relevant collection (e.g. **Raw Samples**).
2. In the Collection table, from the **Columns,** select **Identifier** and the field(s) you want to update (e.g. **Source**), as shown below

![](https://openbis.ch/wp-content/uploads/2022/03/select-colums-for-batch-export-1024x361.png)

3\. If you have several entries you can filter the table (see [Tables](https://openbis.ch/index.php/docs/user-documentation-20-10-3/additional-functionalities/tables/))

4\. **Export** the table choosing the options **Visible Columns, all pages/current page, Rich Text.**

DO NOT export the table in plain text for batch update, otherwise all text formatting will be lost on update!

![](https://openbis.ch/wp-content/uploads/2022/03/batch-update-table-export-1024x349.png)

5\. Modify the file you just exported and save it.

6\. Select **XLS Batch Update Objects** from the **More..** dropdown

![](https://openbis.ch/wp-content/uploads/2022/03/XLS-batch-update-dropdown-1024x476.png)

6\. Upload the file you saved before and click **Accept**. Your entries will be updated.

**Note**: 

If a column is removed from the file or a cell in a column is left empty the corresponding values of updated samples will be preserved.

To delete a value or a parent/child connection from openBIS one needs to enter    ![](https://openbis.ch/wp-content/uploads/2022/03/Screenshot-2022-10-13-at-15.59.01.png)   into the corresponding cell in the XLS file.

## Batch Update Objects

1. Navigate to the relevant collection (e.g. **Raw Samples**).

2\. Select **Batch Update Objects** from the **More...** dropdown.

![](https://openbis.ch/wp-content/uploads/2022/03/batch-update-1-1024x476.png)

3\. Select the relevant _Object_ _type_, e.g. **Sample** 

![](https://openbis.ch/wp-content/uploads/2022/03/old-batch-update.png)

4\. Download the available **template**

5\. Fill in the **identifiers** of the objects you want to update (identifiers are unique in openBIS. This is how openBIS knows what to update). You can copy the identifiers from the identifier column in the table and paste them in the file. Identifiers have this format: /MATERIALS/SAMPLES/SAMPLE1.

6\. Fill in the values in the columns you want to update

7\. Save the file and upload it via the **XLS Batch Update Objects** from the **More..** dropdown

**Note**:

If a column is removed from the file or a cell in a column is left empty the corresponding values of updated samples will be preserved.

To delete a value/connection from openBIS one needs to enter ![](https://openbis.ch/wp-content/uploads/2022/03/Screenshot-2022-10-13-at-15.59.01-1.png) or **\_ \_DELETE\_ \_** into the corresponding cell in the file.
