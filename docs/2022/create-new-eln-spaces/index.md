---
title: "Create new ELN Spaces"
date: "2022-08-02"
---

# Create a new Lab Notebook Space from the ELN UI

From openBIS version 20.10.4 it is possible to create _Spaces_ directly from the ELN interface. To create a new Space under the Inventory:

1. Select **Lab Notebook** in the main menu
2. Click on **+New** **Space** in the Inventory page

    **![](images/labnotebook-space.png)**  

3\. Enter the **Code** for the _Space_, e.g. EQUIPMENT. Please note that codes only accept alphanumeric characters, \-, . , \_.

4\. **Save**    

![](images/create-space.png)    

## Multi-group instances

In a multi-group instance, the _Instance admin_ can choose where to create a new _Space_:

1. **no group**. The new _Space_ will have no prefix and the Settings defined in General Settings will apply (see [General ELN Settings](https://openbis.ch/index.php/docs/admin-documentation/multi-group-set-up/general-eln-settings/)).
2. **in one of the existing groups**. The new _Space_ will have the group prefix and the Settings of that group will apply (see [Group ELN Settings](https://openbis.ch/index.php/docs/admin-documentation/multi-group-set-up/group-eln-settings/)). 

![](images/create-space-no-group.png)

![](images/create-space-groups-dropdown.png)

Use cases where this could be useful:

1. in a multi-group instance with user folders in the Lab Notebook it is desired to have in addition some Spaces that are not linked to a particular user, but maybe rather to some projects, as shown below.
2. in a multi-group instance it is not at all desired to have the lab notebooks organised by users, but rather by projects. A _system admin_ can configure the user management config file not to create users folders in the lab notebook section (see [Multi group instances](https://unlimited.ethz.ch/display/openBISDoc2010/User+Group+Management+for+Multi-groups+openBIS+Instances)).

![](images/no-group-lab-notebook-spaces-multi-group.png)

The rights for _Spaces_ not belonging to any group need to be manually assigned by an _Instance admin_.

# Create a new Lab Notebook Space from the core UI

In the core UI:  

1. Select **Admin -> Spaces**
2. Click **Add Space** at the bottom of the page
3. Enter the Space **Code**, e.g. **EQUIPMENT**
4. **Save**

![](images/spaces-admin-UI-300x158.png)

By default all _Spaces_ created in the core UI are shown under the Lab Notebook part of the ELN UI.
