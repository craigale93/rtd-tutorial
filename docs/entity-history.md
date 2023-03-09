---
title: "Entity history"
date: "2022-02-28"
---

 

Whenever an entity of type _Collection/Experiment_, _Object_ or _Dataset_ is modified in openBIS, the changes are stored in the database. The stored changes are modifications to property fields, addition and deletion of parents/children for _Objects_ and _Datasets_, changes of _Space/Project/Experiment/Object_ ownership if an entity is moved.

The **History** of changes of each entity is now available in the ELN UI. In versions prior to openBIS 20.10.3 this was only available in the core UI.

 

 

## History table for Collections

 

In a _Collection_ page, the **History** can be accessed from the **More..** dropdown list.

 

![](https://openbis.ch/wp-content/uploads/2022/02/history-collection-dropdown.png)

 

The **History** table shows the version number of the changes, the author of the changes, the changes made (with the values before- in red, and after the change - in green), and the timestamp, i.e. the time when the changes were made.

 

For a _Collection_, the **PermID** (Permanent Identifier) of the _Project_ it belongs to is shown. If a _Collection_ is moved from one _Project_ to another, the PermID of the old and new _Projects_ are shown in the history table.

 

 

![](https://openbis.ch/wp-content/uploads/2022/02/Screenshot-2022-02-28-at-22.57.24-1024x535.png)

 

The **show** option in **Full Document** shows the full metadata of the entry (not only the changed fields) when changes were applied. This is displayed in JSON format.

 

![](https://openbis.ch/wp-content/uploads/2022/02/Screenshot-2022-03-04-at-12.47.18-1024x506.png)

 

 

## History table for Objects

 

For every _Object_, the history of changes can be accessed from the **More..** dropdown on the _Object_ page.

 

![](https://openbis.ch/wp-content/uploads/2022/02/object-history-dropdown.png)

 

 

For an _Object_, the **PermID** (Permanent Identifier) of the _Collection_ it belongs to is shown. If an _Object_ is moved from one _Collection_ to another, the PermID of the old and new _Collections_ are shown in the history table.

 

## History table for Datasets

 

For every dataset, the history of changes can be accessed from the **More..** dropdown on the _Dataset_ page.

 

![](https://openbis.ch/wp-content/uploads/2022/02/dataset-history-dropdown.png)

 

For a _Dataset_, the **PermID** (Permanent Identifier) of the _Object_/_Collection_ it belongs to is shown. If a _Dataset_ is moved from one _Object_/_Collection_ to another, the PermID of the old and new _Objects_/_Collections_ are shown in the history table.
