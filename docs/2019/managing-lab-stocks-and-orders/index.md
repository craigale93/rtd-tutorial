---
title: "Managing Lab Stocks and Orders"
date: "2019-09-04"
---

  
It is possible to use openBIS to manage stocks of products and lab orders.  
  

## Register suppliers

> 1. Go to the _Supplier Collection_ folder under _Stock -> Stock Catalog-> Suppliers_ in the main menu.
> 2. Click on the **\+ New Supplier** button in the _Collection_ page.
> 3. Follow the steps explained in the [Register Entries](https://openbis.ch/index.php/docs/user-documentation-19-06-4/inventory/register-objects/) section.

##   
Register products

> 1. Go to the _Product Collection_ folder under _Stock -> Stock Catalog-> Products_ in the main menu.
> 2. Click the **\+ New Product** button in the Collection page.
> 3. Follow the steps explained in the [Register Entries](https://openbis.ch/index.php/docs/user-documentation-19-06-4/inventory/register-objects/) section.
> 4. In addition, a supplier needs to be added as parent. Select a supplier from the list of suppliers registered in the _Supplier Collection_.

##   
Create product requests

> 1. Go to the _Request Collection_ folder under _Stock -> Stock Catalog-> Requests_ in the main menu.
> 2. Click the **\+ New Request** button in the _Collection_ page.
> 3. Fill in the form:
>     1. the _Order status_ is mandatory
>     2. Add a product to the Request from the list of registered ones, by clicking the + button next to _Products_. Alternatively you can also create a new product, by clicking the + button in the _Create and add new product table_.
> 4. Click _Save_ on top of the form.

##   
Create product orders

> 1. Go to the _Order Collection_ folder under _Stock -> Stock Orders-> Orders_ in the main menu.
> 2. Click the **\+ New Order** button in the _Collection_ page.
> 3. If the order template form is defined by a _lab admin_ in the Settings, most fields will be automatically filled. If not, fill in the fields with the relevant information.
> 4. Add one or more requests to the oder, by clicking the + button next to _Requests_. Only requests with _Order status_ set to _not yet ordered_ will be displayed.
> 5. Click _Save_ on top of the form.
> 6. Once the order is processed, change the _Order status_ to _ordered_. This will automatically change the _Order status_ in all connected requests.
