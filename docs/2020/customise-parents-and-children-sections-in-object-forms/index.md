---
title: "Customise Parents and Children Sections in Object Forms"
date: "2020-02-05"
---

  
The **Parents** and **Children** sections are automatically defined in all _Object_ forms. It is possible to customise or remove these sections, from the **Settings**, under **Utilities**.

  
Let's consider an example. The default _Experimental Step_, present in all openBIS instances, looks like the picture below: in the **Parents** section, General Protocol is predefined. If we want to add a General Protocol to the form, we click the + next to General Protocol. If we want to add another link, to a material, for example, we need to click the + next to Parents.

![](images/Screenshot-2020-02-21-at-16.26.35-1024x465.png)

Now let's see how the Experimental Step is configured in the **Object Types Definition Extension** in the **Settings.**

![](images/Screenshot-2020-02-26-at-13.22.59-1024x705.png)

1. **Section Name**. Enter an alternative name for the **Parents** or  **Children** section. If empty the default is used (Parents/Children).
2. **Disable the section** for the _Object_ type. No parents/children can be added to this _Object_ type.
3. **Disable addition of any object type**. This removes the **+** button next to the section name, which enables to add as parent any _Object_ type. In this way only _Objects_ of types pre-defined in the form can be added.
4. To define which _Object_ types should always be shown in the form of a this _Object_ type, click the **+** button.
5. Select if this is a **Parent** or **Child** from the **drop down**.
6. Enter a **Label**, which is what is shown in the _Object_ form.
7. Select the _Object_ type from the **drop down**.
8. Specify the **minimum** and **maximum** number of parents needed as input for this _Object_ type. This can be left empty if parents are not mandatory for this type.
9. Specify A**nnotations** (e.g. Comments) for this parent _Object_ type.
10. Click the + button on the section to add an annotation field.
11. Select the **Annotation** field from the list of available fields.
12. Specify if the **Annotation** is mandatory.

  
The figure below shows how the **Annotation** of type **Comments** looks like in the _Experimental Step_ form.

![](images/exp-step-gen-prot-selected-comment-field-1024x475.png)
