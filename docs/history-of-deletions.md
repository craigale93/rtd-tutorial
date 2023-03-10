---
title: "History of deletions"
date: "2022-03-04"
---

 

When _Experiments/Collections_, _Objects_ and _Datasets_ in openBIS are permanently deleted, i.e. they are removed from the trashcan, the information of these permanently deleted entries is stored in the database and it is visible in the admin UI.

_Spaces_ and _Projects_ are directly permanently deleted, without going to the trashcan. Their information is also shown in the table of history of deletions in the admin UI.

 

The table of history of deletions is under the **Tools** section, as shown below.

 

For each deleted entry, the table shows:

1. **Entity type**: this can be _Space_, _Project_, _Collection, Object, Dataset;_
2. **Entity identifier**: this is the PermID of the entity. _Spaces_ do not have PermID, so the code of the _Space_ is shown instead;
3. **Entity Space**: the _Space_ to which the entity belonged;
4. **Entity Project**: the _Project_ to which the entity belonged;
5. **Entity Registrator**: the user who registered the entity;
6. **Entity Registration Date**: the date of registration of the entity;
7. **Reason**: the reason of deletion of the entity;
8. **Description**: the PermID (_Collection_, _Object_), identifier (_Space_, _Project_),  dataset path (_Dataset_) of the entity;
9. **Content**: the metadata of the entity when it was deleted. This is available for _Projects_, _Collections_, _Objects_, _Datasets_, but not for _Spaces_;
10. **User**: the user who deleted the entity;
11. **Date**: the date and time of deletion of the entity.

 

![](https://openbis.ch/wp-content/uploads/2022/02/history-deletion-1024x507.png)
