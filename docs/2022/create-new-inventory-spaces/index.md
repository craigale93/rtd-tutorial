---
title: "Create new Inventory Spaces"
date: "2022-02-23"
---

  
The default Inventory contains two folders: **Materials** and **Methods**. These are openBIS _Spaces_.

Additional _Spaces_ can be created by an _Instance admin_.

# Create a new Inventory Space from the ELN UI

From openBIS version 20.10.4 it is possible to create _Spaces_ directly from the ELN interface.

To create a new _Space_ under the Inventory:

1. Select **Inventory** in the main menu
2. Click on **+New Inventory Space** in the Inventory page

![](images/inventory-space.png)

3\. Enter the **Code** for the _Space_, e.g. EQUIPMENT. Please note that codes only accept alphanumeric characters, \-, . , \_.

4\. **Save**

![](images/create-space.png)

## Multi-group instances

In a multi-group instance, the _Instance admin_ can choose where to create a new _Space_:

1. **no group**. The new _Space_ will have no prefix and the Settings defined in General Settings will apply (see [General ELN Settings](https://openbis.ch/index.php/docs/admin-documentation/multi-group-set-up/general-eln-settings/)).
2. **in one of the existing groups**. The new _Space_ will have the group prefix and the Settings of that group will apply (see [Group ELN Settings](https://openbis.ch/index.php/docs/admin-documentation/multi-group-set-up/group-eln-settings/)).

![](images/create-space-no-group.png)

![](images/create-space-groups-dropdown.png)

# Create a new Inventory Space from the core UI

In the core UI:

1. Select **Admin -> Spaces**
2. Click **Add Space** at the bottom of the page
3. Enter the _Space_ **Code**, e.g. **EQUIPMENT**
4. **Save**

![](images/spaces-admin-UI-300x158.png)

## Set Inventory Spaces

  
When new _Spaces_ are created in the core UI, they are automatically displayed under the _Lab Notebook_ part of the ELN main menu.

It is possible to move a new _Space_ to the Inventory, by editing the **Settings** under **Utilities** in the **ELN UI:**

1. Go to the **Settings** and click **Edit.**
2. Go to the **Inventory Spaces** section in the **Settings** and click the **+** button as shown below.
3. Select the _Space_ you want to move to the _Inventory_ from the list of available _Spaces_.
4. **Save** the Settings.
5. Refresh the browser.

![](images/move-space-to-inventory-1024x426.png)
