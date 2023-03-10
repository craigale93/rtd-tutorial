---
title: "Managing Lab Stocks and Orders"
date: "2020-02-05"
---

  
It is possible to use openBIS to manage stocks of products and lab orders.  
  

## Register suppliers

> 1. Go to the _Supplier Collection_ folder under _Stock -> Stock Catalog_ in the main menu.
> 2. Click the + button in the Collection page.
> 3. Follow the steps explained in the [Register Objects](#registerobject) section

##   
Register products

> 1. Go to the _Product Collection_ folder under _Stock -> Stock Catalog_ in the main menu.
> 2. Click the + button in the Collection page.
> 3. Follow the steps explained in section .
> 4. In addition, a supplier needs to be added as parent. Select a supplier from the list of suppliers registered in the _Supplier Collection_.

##   
Create product requests

> 1. Go to the _Request Collection_ folder under _Stock -> Stock Catalog_ in the main menu.
> 2. Click the + button in the Collection page.
> 3. Fill in the form:
>     1. the _Order status_ is mandatory
>     2. Add a product to the Request from the list of registered ones, by clicking the + button next to _Products_. Alternatively you can also create a new product, by clicking the + button in the _Create and add new product table_.
> 4. Click _Save_ on top of the form.

##   
Create product orders

> 1. Go to the _Order Collection_ folder under _Stock -> Stock Orders_ in the main menu.
> 2. Click the + button in the Collection page.
> 3. If the order template form is defined by and Admin in the Settings, most fields will be automatically filled. If not, fill in the fields with the relevant information.
> 4. Add one or more requests to the oder, by clicking the + button next to Requests. Only requests with _Order status_ set to _not yet ordered_ will be displayed.
> 5. Click _Save_ on top of the form.
> 6. Once the order is processed, change the _Order status_ to _ordered_. This will automatically change the _Order status_ in all connected requests.
