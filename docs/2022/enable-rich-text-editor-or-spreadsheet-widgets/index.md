---
title: "Enable Rich Text Editor or Spreadsheet Widgets"
date: "2022-03-04"
---

  
For certain fields, it is possible to enable the use of a Rich Text Editor (RTE) or a spreadsheet component. _Instance admin_ rights are necessary for this.

  
The **RTE** can be enabled for properties of type **MULTILINE\_VARCHAR**. The **spreadsheet component** can be enabled for properties of type **XML**.

  
Procedure:  
  

1. Properties are defined when creating new entity types (_Datasets_, _Objects_, _Experiments/Collections_)
2. To set a property as RTE or spreadsheet go to the **Settings**, under **Utilities**
3. Select /ELN\_SETTINGS/GENERAL\_ELN\_SETTINGS
4. Enable editing and scroll down to the **Custom Widgets** section
5. Click the + button on the same line as **Property Type** and **Widget**, as shown below
6. A new field will appear where you can select the property type and the widget. Choices are: **Word Processor** (=RTE) or **Spreadsheet.**

![](images/custom-widget-gen-settings-1024x293.png)
