---
title: "Create Collections of Materials"
date: "2022-02-23"
---

_Collections_ are folders used to organise _Objects_ in the **Materials** Inventory. Such _Objects_ can be different types of samples and materials (e.g. chemicals, antibodies, batteries, environmental samples).

_Collections_ need to be created inside another folder, called _Project_, in the **Materials** inventory.

For example, if we want to create a collection of raw samples, we need to adopt the following steps:

1. Create an _Object_ _type_ called Sample. This can only be done by an _Instance admin_, from the admin interface, as explained here: [New Entity Type Registration](https://openbis.ch/index.php/docs/admin-documentation-openbis-19-06-4/new-entity-type-registration/)
2. Create a first folder called Samples inside the **Materials** folder _(Project)_
3. Create a second folder called Raw Samples _(Collection)_

To create the _Project_ folder:

> 1. Click on the **Materials** folder
> 2. Click the **\+ New Project** button in the form.
>     
>     ![](https://openbis.ch/wp-content/uploads/2022/02/create-samples-project.png)
>     
> 3. Provide a description, if wanted. This is not mandatory.
> 4. Enter the **Code**. This will be the name of the folder, in this case SAMPLES. Codes only take alphanumeric characters and no spaces. 

To register the _Collection_ folder, inside the _Project_ folder:

> 1. Click on the _Project_ folder, in this case **Samples**.
> 2. Click the **\+ New** button in the main form and choose **Collection** from the dropdown.
>     
>     ![](https://openbis.ch/wp-content/uploads/2022/02/create-raw_samples-collection.png)
> 3. Replace the automatically generated **Code** with something pertinent to the collection (e.g SAMPLES)
> 4. Fill in the **Name** field (e.g. Raw Samples). Note that by default, the navigation menu on the left shows the name. If the name is not provided, the code is shown.
> 5. Select the **Default object type** from the list of available types. This is the _Object_ for which the _Collection_ is used. In this case, **Sample**.
> 6. Select the **Default collection view** (see **[Customise Collection View](https://openbis.ch/index.php/docs/user-documentation-20-10-3/lab-notebook/customise-collection-view/))**
