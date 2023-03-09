---
title: "User Registration"
date: "2022-02-23"
---

# Register users in ELN Interface

Users can only be registered by someone with _Instance admin_ role:

> 1. Go to the **User Manager**, under **Utilities**.
> 2. Click the  +**New** **User** button. 
> 3. Provide a username: LDAP username for LDAP authentication, email for SSO authentication.
> 4. For file-based authentication provide username and password. The password can later be changed by the user.

![](images/ELN-user-manager-1024x398.png)

## ![](images/Screenshot-2020-02-26-at-10.34.35.png)

## Default roles assigned in ELN

  
When a user is registered via the ELN interface, a _Space_ (folder) with the name of the user is automatically created under the Lab Notebook main menu. The user is also assigned some default roles:

1. _Space admin_ of the _Space_ created for him/her under the notebook.
2. _Space user of_ the Inventory _Spaces_ (MATERIALS, METHODS by default), the STOCK\_CATALOG and the STORAGE _Spaces_.
3. _Space Observer_ of the STOCK\_ORDERS, ELN\_SETTINGS and PUBLICATIONS S_paces_. 

Modification to default rights can be granted by an _Instance admin_ from the _admin UI_, as explained below.

Overview of roles: [https://openbis.ch/index.php/docs/admin-documentation/user-registration/openbis-roles/ .](https://openbis.ch/index.php/docs/admin-documentation/user-registration/openbis-roles/)

# Register users from the admin UI

When users are registered via the admin UI no default roles are assigned.

To register new users from the admin UI:

1. go to the **Users** tab. The **Users** and **Groups** will show in the main menu on left had side.
2. Click on **Users** in the menu: the **Add** button at the bottom of the menu will become active (blue)
3. Click the **Add** button
4.  Enter the U**ser Id**. This is the LDAP username, when LDAP authentication is used, or the email address if SSO is used. Please note that file-based authentication (where username and password can be created) is not supported by the admin UI.
5. **Home space**: this sets the default folder a user sees marked as **My Space** in the Lab Notebook.
6. Click the **Add Role** button at the bottom of the page to assign a role to the user.
7. Click the **Add Group** button at the bottom of the page to assign a user to a group of users.

![](images/admin-ui-add-users.png)

8\. To assign a role to a user, first the **Level** needs to be selected (Instance, Space, Project) .

9.If level is Instance, you can directly select a role (Admin, Observer). If the level is Space or Project, you first need to select the Space or Project and then assign a [Role](https://openbis.ch/index.php/docs/admin-documentation/user-registration/openbis-roles/).

![](images/admin-ui-roles-300x293.png)

10\. Multiple roles can be assigned to a user. 

11\. Roles can be removed from the **Remove** button at the bottom of the page. 

12\. After making the necessary changes, press the **Save** button.

![](images/admin-ui-remove-role-save-1024x564.png)

# Create Users groups in admin UI

It is possible to create groups of users and assign rights to a group:

1. go to the **Users** tab. The **Users** and **Groups** will show in the main menu on left had side.
2. Click on **Groups** in the menu: the **Add** button at the bottom of the menu will become active (blue)
3. Click the **Add** button
4. Enter a **Code** for the group. This is the equivalent of a name, but Codes can only contain numbers, letters and the following symbols: . - \_
5. You can now assign registered users to the group and assign Roles as explained above.

![](images/admin-ui-groups-1-1024x559.png)
