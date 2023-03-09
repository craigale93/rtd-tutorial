---
title: "Group ELN Settings"
date: "2022-09-23"
---

 

In a multi group instance a _group admin_ or _Instance admin_ can customise the ELN Settings for the group.

 

The group Settings can be selected from the **Settings** in the main menu.

 

![](images/settings-main-menu.png)

The Settings for the relevant group can be selected from the available dropdown, as shown below.

 

![](images/group-settings-selection.png)

 

 

In the group settings the following is configurable:

 

1. **Storages**. In this section the group storages for samples can be created, as described in [Configure Lab Storage;](https://openbis.ch/index.php/docs/admin-documentation/customise-inventory-of-materials-and-samples/configure-lab-storage/)
2. **Templates**. In this section, the templates for a given _Object type_ can be created, as described in [Create Templates for Objects](https://openbis.ch/index.php/docs/admin-documentation/create-templates-for-objects/);
3. **Object types definition extension**. In this section, it is possible to:
    1. Define if one _Object type_ is a protocol. If an _Object type_ is defined as a protocol, it is possible to create a local copy of it under an Experiment, when linking to it as a parent, as described in [Enable Protocols in Settings;](https://openbis.ch/index.php/docs/admin-documentation/customise-inventory-of-protocols/enable-protocols-in-settings/)
    2. Enable the storage widget for an _Object type,_ as described in [Enable Storage Widget on Sample Forms](https://openbis.ch/index.php/docs/admin-documentation/customise-inventory-of-materials-and-samples/enable-storage-widget-on-sample-forms/)
    3. Define if the _Object type_ should be shown in drop downs, as described in [Enable Objects in dropdowns](https://openbis.ch/index.php/docs/admin-documentation/new-entity-type-registration/enable-objects-in-dropdowns/);
    4. Define if the _Object type_ should be shown in the main menu under the Lab notebook section. By default objects are not shown in the main menu in the Inventory section.
    5. Customise the Parents and Children sections for an _Object type_ as described in [Customise Parents and Children Sections in Object Forms](https://openbis.ch/index.php/docs/admin-documentation/customise-parents-and-children-sections-in-object-forms/);
4. **Inventory Spaces**. It is possible to move Spaces from the Inventory section to the Lab notebook section and vice-versa as described in [Move Spaces between Lab Notebook and Inventory](https://openbis.ch/index.php/docs/admin-documentation/space-management/move-space-between-lab-notebook-and-inventory/)
5. **Main menu**. The main menu for the group can be customised here, as described in [Customise the Main Menu;](https://openbis.ch/index.php/docs/admin-documentation/customise-the-main-menu/)
6. **Miscellaneous**. In this section it is possible to:
    1. Show the dataset archiving buttons for the group. Please note that this is not available by default, but the infrastructure for [archiving to tapes](https://openbis.ch/index.php/docs/user-documentation/data-archiving/) (StrongBox/StrongLink) needs to be put in place by a _system admin ([Multi data set archiving](https://unlimited.ethz.ch/display/openBISDoc2010/Multi+data+set+archiving))_.
    2. Hide sections by default. By default some sections in some forms are hidden:
        1. Description in _Spaces_ and _Projects_.
        2. Identification info in _Spaces_, _Projects_, _Experiments_, _Objects_, _Datasets_.

By unchecking this option, these sections will be shown by default.
