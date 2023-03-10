---
title: "Freeze Entities"
date: "2022-03-04"
---

  
Each level of the openBIS hierarchy (Space, Project, Experiment/Collection, Object, Dataset) can be frozen, so it can be no longer edited and/or deleted.

At every level, everything contained underneath is selected by default to be frozen. E.g. if I choose to freeze a Space, everything contained in the Space is automatically selected to be frozen. Single entities can be manually unselected.

A Space admin role is necessary to freeze entities in a given Space.  
  

**IMPORTANT: the freezing is IRREVERSIBLE!**  
  

This operation cannot be undone from any UI, not even by an _Instance admin._ Please freeze entities only when you are absolutely sure that they should not be further modified!

##   
**How to freeze an entity**

  
At each level of the openBIS hierarchy (Space, Project, Experiment/Collection, Object, Dataset) the **Freeze Entity** option is available under the **More..** dropdown menu. See the example for a Space below.

![](https://openbis.ch/wp-content/uploads/2022/03/freezing-space.png)

If you select this, a list of entities contained or connected to the one selected will be presented to you, as shown below. By default everything is selected, so you need to unselect entries that you do not want to freeze.

![](https://openbis.ch/wp-content/uploads/2019/06/freze-selection-1024x469.png)

To freeze one or several entities, you need to provide your login password and save.

**Rules for freezing**

1. **Freeze Space only**

<table width="841"><tbody><tr><td width="194"><p>&nbsp;</p></td><td width="179"><p>Allowed</p></td><td width="179"><p>Not allowed</p></td></tr><tr><td width="194"><p>Create new Project</p></td><td width="179"><p>&nbsp;</p></td><td width="179"><p>x</p></td></tr><tr><td width="194"><p>Create new Experiment/Collection</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Create new Object</p></td><td width="179"><p>&nbsp;</p></td><td width="179"><p>x</p></td></tr><tr><td width="194"><p>Create new Dataset in existing Experiment/Collection</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Create new Dataset in existing Object</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Edit existing Project</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Edit existing Experiment/Collection</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Edit existing Object</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Edit existing Dataset</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Delete Space</p></td><td width="179"><p>&nbsp;</p></td><td width="179"><p>x</p></td></tr><tr><td width="194"><p>Delete Project</p></td><td width="179"><p>&nbsp;</p></td><td width="179"><p>x</p></td></tr><tr><td width="194"><p>Delete Experiment/Collection</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Delete Object</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Delete Dataset</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Move Experiment/Collection</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Move Object</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr><tr><td width="194"><p>Copy Object</p></td><td width="179"><p>&nbsp;</p></td><td width="179"><p>x</p></td></tr><tr><td width="194"><p>Export</p></td><td width="179"><p>x</p></td><td width="179"><p>&nbsp;</p></td></tr></tbody></table>

2. **Freeze Project only**

<table><tbody><tr><td><p>&nbsp;</p></td><td><p>Allowed</p></td><td><p>Not allowed</p></td></tr><tr><td><p>Create new Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Create new Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Create new Dataset in existing Experiment/Collection</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Create new Dataset in existing Object</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Edit Project</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Edit existing Experiment/Collection</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Edit existing Object</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Edit existing Dataset</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Delete Project</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Dataset</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Move Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Move Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Copy Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Export</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr></tbody></table>

**3\. Freeze Experiment/Collection only**

<table><tbody><tr><td><p>&nbsp;</p></td><td><p>Allowed</p></td><td><p>Not allowed</p></td></tr><tr><td><p>Create new Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Create new Dataset in existing Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Create new Dataset in existing Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Edit existing Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Edit existing Object</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Edit existing Dataset</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Delete Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Dataset</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Move Experiment/Collection</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Move Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Copy Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Export</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr></tbody></table>

**4\. Freeze Object only**

<table><tbody><tr><td><p>&nbsp;</p></td><td><p>Allowed</p></td><td><p>Not allowed</p></td></tr><tr><td><p>Create new Dataset in existing Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Edit existing Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Edit existing Dataset in Object</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Delete Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Dataset</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Move Object</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Copy Object</p></td><td><p>x (only if the Experiment is not frozen)</p></td><td><p>&nbsp;</p></td></tr><tr><td><p>Export</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr></tbody></table>

**5\. Freeze Dataset only**   
  

<table><tbody><tr><td><p>&nbsp;</p></td><td><p>Allowed</p></td><td><p>Not allowed</p></td></tr><tr><td><p>Edit existing Dataset</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Delete Dataset</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Move Dataset</p></td><td><p>&nbsp;</p></td><td><p>x</p></td></tr><tr><td><p>Export</p></td><td><p>x</p></td><td><p>&nbsp;</p></td></tr></tbody></table>

##
