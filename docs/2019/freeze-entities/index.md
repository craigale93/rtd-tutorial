---
title: "Freeze Entities"
date: "2019-09-04"
---

  
Each level of the openBIS hierarchy (Space, Project, Experiment/Collection, Object, Dataset) can be frozen, so it can be no longer edited and/or deleted.

At every level, everything contained underneath is selected by default to be frozen. E.g. if I choose to freeze a Space, everything contained in the Space is automatically selected to be frozen. Single entities can be manually unselected.

A Space admin role is necessary to freeze entities in a given Space.  
  

**IMPORTANT: the freezing is IRREVERSIBLE!**  
  

This operation cannot be undone from any UI, not even by an _Instance admin._ Please freeze entities only when you are absolutely sure that they should not be further modified!

##   
**How to freeze an entity**

  
Each level of the openBIS hierarchy has a lock icon in the menu toolbar, as shown below.

![](images/freeze-hierarchy-300x140.png)

Click on the icon and a list of entities contained or connected to the one selected will be presented to you, as shown below.

![](images/freze-selection-300x137.png)

Provide your login password and save.

##   
Rules for freezing  
  

1. **Freeze Space only**

<table style="height: 634px;" border="1" width="841"><tbody><tr><td width="194">&nbsp;</td><td width="179"><span style="color: #000000;">Allowed</span></td><td width="179"><span style="color: #000000;">Not allowed</span></td></tr><tr><td width="194"><span style="color: #000000;">Create new Project</span></td><td width="179">&nbsp;</td><td width="179"><span style="color: #000000;">x</span></td></tr><tr><td width="194"><span style="color: #000000;">Create new Experiment/Collection</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Create new Object</span></td><td width="179">&nbsp;</td><td width="179"><span style="color: #000000;">x</span></td></tr><tr><td width="194"><span style="color: #000000;">Create new Dataset in existing Experiment/Collection</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Create new Dataset in existing Object</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Edit existing Project</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Edit existing Experiment/Collection</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Edit existing Object</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Edit existing Dataset</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Delete Space</span></td><td width="179">&nbsp;</td><td width="179"><span style="color: #000000;">x</span></td></tr><tr><td width="194"><span style="color: #000000;">Delete Project</span></td><td width="179">&nbsp;</td><td width="179"><span style="color: #000000;">x</span></td></tr><tr><td width="194"><span style="color: #000000;">Delete Experiment/Collection</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Delete Object</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Delete Dataset</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Move Experiment/Collection</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Move Object</span></td><td width="179"><span style="color: #000000;">x</span></td><td width="179">&nbsp;</td></tr><tr><td width="194"><span style="color: #000000;">Copy Object</span></td><td width="179">&nbsp;</td><td width="179"><span style="color: #000000;">x</span></td></tr></tbody></table>

  
**2\. Freeze Project only**  
  

<table class="wp-block-table"><tbody><tr><td>&nbsp;</td><td><span style="color: #000000;">Allowed</span></td><td><span style="color: #000000;">Not allowed</span></td></tr><tr><td><span style="color: #000000;">Create new Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Create new Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Create new Dataset in existing Experiment/Collection</span></td><td><p style="text-align: left;"><span style="color: #000000;">x</span></p></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Create new Dataset in existing Object</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Edit Project</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Edit existing Experiment/Collection</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Edit existing Object</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Edit existing Dataset</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Delete Project</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Dataset</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Move Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Move Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Copy Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr></tbody></table>

  
**3\. Freeze Experiment/Collection only**  
  

<table class="wp-block-table"><tbody><tr><td>&nbsp;</td><td><span style="color: #000000;">Allowed</span></td><td><span style="color: #000000;">Not allowed</span></td></tr><tr><td><span style="color: #000000;">Create new Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Create new Dataset in existing Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Create new Dataset in existing Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Edit existing Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Edit existing Object</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Edit existing Dataset</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Delete Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Dataset</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Move Experiment/Collection</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Move Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Copy Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr></tbody></table>

  
**4\. Freeze Object only**  
  

<table class="wp-block-table"><tbody><tr><td>&nbsp;</td><td><span style="color: #000000;">Allowed</span></td><td><span style="color: #000000;">Not allowed</span></td></tr><tr><td><span style="color: #000000;">Create new Dataset in existing Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Edit existing Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Edit existing Dataset in Object</span></td><td><span style="color: #000000;">x</span></td><td>&nbsp;</td></tr><tr><td><span style="color: #000000;">Delete Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Dataset</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Move Object</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Copy Object</span></td><td><span style="color: #000000;">x (only if the Experiment is not frozen)</span></td><td>&nbsp;</td></tr></tbody></table>

  
**5\. Freeze Dataset only**  
  

<table class="wp-block-table"><tbody><tr><td>&nbsp;</td><td><span style="color: #000000;">Allowed</span></td><td><span style="color: #000000;">Not allowed</span></td></tr><tr><td><span style="color: #000000;">Edit existing Dataset</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Delete Dataset</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr><tr><td><span style="color: #000000;">Move Dataset</span></td><td>&nbsp;</td><td><span style="color: #000000;">x</span></td></tr></tbody></table>
