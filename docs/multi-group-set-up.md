---
title: "Multi-group set up"
date: "2022-09-23"
---

 

openBIS can be configured to be used by multiple groups, where every group only sees their own group _Spaces_.

This configuration needs to be done by a _system admin_, as described [here](https://unlimited.ethz.ch/display/openBISDoc2010/User+Group+Management+for+Multi-groups+openBIS+Instances).

 

In the example below we see two groups: **G1** and **G2**. For each group, in the Inventory, there are a **Materials**, a **Methods** and a **Publications** _Spaces_ with the group prefix. In the lab notebook, each group member has a personal _Space_ where the name is the group prefix and the username of the user.

 

It is possible to configure the user management configuration file (_sys admin_) not to create user _Spaces_ for a given group, in case one group prefers to organise their notebook by project, rather than by group members, as described [here](https://unlimited.ethz.ch/display/openBISDoc2010/User+Group+Management+for+Multi-groups+openBIS+Instances).

 

![](https://openbis.ch/wp-content/uploads/2022/09/multi-group-menu.png)

In a multi group instance users are automatically registered and the roles defined in the user management configuration file on the server are automatically assigned to them. There is a maintenance task that runs in the background at a frequency determined by the _system admin_. This can be once per day or several times per day. If there are new users, they will be added to openBIS when the maintenance task runs.

 

An _instance admin_ can assign additional roles to users from the admin interface ([User Registration](https://openbis.ch/index.php/docs/admin-documentation/user-registration/)). Default roles defined in the user management configuration file and automatically assigned cannot be removed, because they will be assigned again automatically by openBIS when the maintenance task runs.

 

We would recommend to assign _SPACE\_USER_ rights for the Inventory _Spaces_ to every group user and _SPACE\_ADMIN_ rights for their own lab notebook. This can be specified in the user management configuration file by the _system admin_.

 

In the user management configuration file, one or more admins for each group can be designated. The _group admin_ has by default _SPACE\_ADMIN_ rights to all the _Spaces_ of their group. A _group admin_ can customise the [Group ELN Settings](https://openbis.ch/index.php/docs/admin-documentation/multi-group-set-up/group-eln-settings/) for the group.
