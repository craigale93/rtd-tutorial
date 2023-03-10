---
title: "Advanced search"
date: "2022-07-28"
---

The **Advanced Search** can be accessed from the main menu, under **Utilities**. Alternatively, the advanced search can also be used after performing a global search (see [Search](https://openbis.ch/index.php/docs/user-documentation-20-10-3/search/)), to refine the obtained results.

![](https://openbis.ch/wp-content/uploads/2022/07/advanced-search-main-menu.png)

In the advanced search users can combine several search criteria using either the **AND** or **OR** operators. Users can choose to search for:

1. **All (prefix match, faster)**: search for the first 3 letters of a word. The search is performed across all fields of all entities (Experiments/Collections, Objects, Datasets).
2. **All (full word match, faster)**: search for a complete word. The search is performed across all fields of all entities (Experiments/Collections, Objects, Datasets).
3. **All (partial match, slower)**: search for a partial word. The search is performed across all fields of all entities (Experiments/Collections, Objects, Datasets).
4. **Experiment/Collection**: search is performed across all fields of all Experiments/Collections.
5. **Object**: search is performed across all fields of all Objects.
6. **Dataset**: search is performed across all fields of all Datasets.
7. **A specific Object type** (e.g. Antibody, Bacteria, Cell Line, in the picture below): search is performed across all fields of the selected Object type only.

![](https://openbis.ch/wp-content/uploads/2022/03/advanced-search-criteria.png)

After selecting what to search for, the search can be further restricted to specific fields, in the **Field Type** drop down menu. The available fields for a search vary depending on what the search is performed.

## Search for: All 

This includes all 3 "All" options described above. 

Available **Field Types**:

1. **All**: search across all fields of all entities. 

    ![](https://openbis.ch/wp-content/uploads/2022/03/advanced-search-all-field-type.png)

In this case, this is the only available option and it is not possible to restrict the search.

## Search for: Experiment/Collection

Available **Field Types**:

1. **All**: search across all fields of all Experiments/Collections
2. **Property**: Can select a specific property to search on. This can be selected in the **Field Name**.

![](https://openbis.ch/wp-content/uploads/2022/03/advanced-search-experiment-field-type.png)  

If **Property** is selected in the **Field Type**, a list of all available properties becomes available in the **Field Name** drop down. According to the type of property selected, the comparator operator will be different (e.g for a date field it is possible to select an exact date, or everything before a given date or everything after). It is possible to search on more than one field by clicking on the **+** button in the table and build complex queries in this way.

![](https://openbis.ch/wp-content/uploads/2022/03/advanced-search-experiment-field-type-property-1024x430.png)    

## Search for: Object

Available **Field Types**:

1. **All**: search across all fields of all Objects
2. **Property**: can select one or more specific properties to search on. These can be selected in the **Field Name** (see above)
3. **Experiment/Collection**: search for Objects in a given Experiment/Collection 
4. **Parent**: search for Objects that have the specified parents
5. **Children**: search for Objects that have the specified children

![](https://openbis.ch/wp-content/uploads/2022/07/advanced-search-object-field-type.png)

## Search for: Dataset

Available **Field Types**:

1. **All**: search across all fields of all Datasets
2. **Property**: can select one or more specific properties to search on. These can be selected in the **Field Name** (see above)
3. **Object**: search for Datasets in a given Object 
4. **Experiment/Collection**: search for Datasets in a given Experiment/Collection 

![](https://openbis.ch/wp-content/uploads/2022/07/advanced-search-dataset-field-type.png)

## Search for: specific Object Type (e.g Experimental Step)

In this case, the available Field Types are the same as when searching for an Object.

Available **Field Types**:

1. **All**: search across all fields of the specific Object type (e.g. Experimental Step)
2. **Property**: can select one or more specific properties to search on. These can be selected in the **Field Name** (see above)
3. **Experiment/Collection**: search for Objects of the selected type in a given Experiment/Collection 
4. **Parent**: search for Objects of the selected type that have the specified parents
5. **Children**: search for Objects of the selected type that have the specified children

![](https://openbis.ch/wp-content/uploads/2022/07/advanced-search-expsetp-field-type.png)

# Search Collection

It is possible to launch an advanced search limited to Objects of one Collection from a Collection page, by selecting **Search in Collection** from the **More** drop down. This redirects to the Advanced Search page where the Collection is already pre-defined.

![](https://openbis.ch/wp-content/uploads/2022/03/search-in-collection-1024x378.png)
