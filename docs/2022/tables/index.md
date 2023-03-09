---
title: "Tables"
date: "2022-02-28"
---

  
All tables in the ELN have a similar format and functionalities. The tables have been redesigned for the 20.10.3 release of openBIS.

We give here an overview of the main functionalities of the tables:

> **Filters**_._ Two filter options are available form the **Filters** button: **Filter Per Column** and **Global Filter**. The first allows to filter on individual columns, or multiple columns, whereas the second filters terms across the entire table using the **AND** or **OR** operator. 
> 
> ![](images/filter-per-column-tables-1024x248.png)
> 
> ![](images/global-filter-tables-1024x219.png)

> **Sorting.** It is possible to sort individual columns or also multiple columns. For multi-column sorting, you should click on the column header and press the **Cmd** keyboard key. The order of sorting is shown by a number in each column, as shown below.

![](images/multi-colums-sorting-1024x334.png)

> **Exports.** Tables can be exported in different ways:
> 
> - **Columns**: It is possible to select only **visible columns** or **all columns**.
> - **Rows**: it is possible to select **all page**s, only the **current page**, or **selected rows**.
> - **Values**: it is possible to choose if the export should be in **Plain Text** or **Rich Text**. This refers to text fields with the rich text editor enabled. These properties are stored in the database with HTML tags. If **Rich Text** export is selected the tags will be exported. If **Plain Text** is selected the tags are removed from the export. If you export with the intention of reimporting the file in openBIS (e.g. for batch update), you must export with Rich Text, so text formatting will not be lost on import. Please note that if a field with the Rich Text Editor enabled exceeds a certain number of characters (32767), this will not be exported. IN such case, the user will receive a notification and the corresponding cell with the missing information will be coloured in red in the exported Excel file.
> 
> Tables are exported to **XLS** format. Exported tables can be used for updates via the **XLS Batch Update Objects**. 
> 
> ![](images/Screenshot-2022-02-28-at-11.03.20-1-1024x376.png)
> 
> **Columns**_._ Users can select which properties to display in the table clicking on the **Columns** button. It is also possible to show all properties or hide all properties. The position of the columns can also be changed by placing the cursor next to the = sign in the list and moving the fields. This information is stored in the database for each user.

![](images/columns-in-tables-1024x571.png)

> **Spreadsheets.** If a table contains _Objects_ which have a spreadsheet field which is filled in, a spreadsheet icon is displayed in the table. Upon clicking on the icon, the content of the spreadsheet can be expanded.  
> 
>  ![](images/Screenshot-2022-03-02-at-00.16.41-1024x411.png)
> 
> ![](images/Screenshot-2022-03-02-at-00.17.26-1024x467.png)
> 
> **Text fields**. If a table contains Objects which have long text fields, only the beginning of the text is shown and can be expanded. If the text contains a picture or a table, an icon is shown in the table and the content of the text becomes visible by clicking on the icon.
> 
> ![](images/Screenshot-2022-03-01-at-23.57.58-1024x398.png)
> 
> **Selection of entries in table.** Single entries in a table can be selected using the checkbox in the row. By clicking the checkbox in the table header, all entries of the table are selected. After selection of entries, some actions become available:
> 
> - **Delete**: allows to move the selected entries to the trashcan.
> - **Move**: allows to move the selected entries to a different _Collection/Experiment._
> - **Generate barcodes**: allows to generate custom barcodes for the selected entries.
> - **Update custom barcodes**: allows to update existing custom barcodes of the selected entries.
> - **Clear selection**: allows to clear the selection made.

![](images/selection-entries-table-1024x425.png)

In _Object_ tables inside _Experiments/Collections_ there is an **Operations** column, which allow users to perform certain tasks on an _Object_:

> 1. Upload a file to the _Object_
> 2. Move the _Object_ to another Experiment/Collection.
> 3. Open the hierarchy graph. This is the graph showing parent/child connections of the _Object_.
> 4. Open the hierarchy table. This is the table showing parent/child connections of the _Object_.

![](images/operations-column-1024x405.png)
