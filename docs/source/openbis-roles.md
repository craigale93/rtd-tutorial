---
title: "openBIS roles"
date: "2022-03-04"
---

 

## Observer

This role can be assigned to the whole openBIS instance (_Instance Observer_) or to specific Spaces or Projects (_Space_ or _Project Observer_). Users with this role have read-only access to the whole openBIS (_Instance Observer_), or to a specified Space or Project (_Space_ or _Project Observer_).

Observer can:

- list
    - persons
    - spaces
    - projects
    - sample types
    - experiment types
    - data types
    - file format types
    - material types
    - data set types
    - samples
    - experiments
    - data sets
    - materials
    - property types
    - vocabularies
    - vocabulary terms
    - attachments
    - data store services
- get details of
    - project
    - sample
    - experiment
    - data set
    - material
- download
    - attachment
    - sample registration template
- upload data set to CIFEX
- create report for data sets
- search for
    - samples
    - experiments
    - materials
    - data sets

 

## Space/Project User

Extends Observer permissions with some creating and editing functionality. Permissions are limited to specified Space(s) or Project(s).

Can do everything that Observer and additionally:

- create
    - sample
    - experiment
- edit
    - sample
    - experiment
    - project

 

## Space/Project Power User

Extends Space/Project User permissions with some deleting, editing and processing functionality. Permissions are limited to specified Space(s) or Project(s).

Can do everything that Space/Project User and additionally:

- create project
- delete
    - project
    - data sets
    - samples
    - experiments
    - attachments
- edit attachments
- process data sets
- add, update and delete vocabulary terms

 

Please note that this role cannot be assigned via the ELN UI, only via admin UI.

 

## Space/Project Admin

Extends Space/Project Power User permissions allowing to manage roles and projects inside given Space(s) or Project(s).

Can do everything that Space/Project Power User and additionally:

- list roles
- create and delete space role
- edit data set

 

## Instance Admin

Has the full access to given OpenBIS instance.

Can do everything that Space/Project Admin and additionally:

- create
    - space
    - material
    - person
    - property type
    - vocabulary
    - material type
    - sample type
    - experiment type
    - data set type
    - file format type
- create/delete instance admin role
- edit
    - material
    - property type
    - property type assignment
    - vocabulary
    - material type
    - sample type
    - experiment type
    - data set type
    - file format type
- assign/unassign property type
- delete
    - space
    - vocabulary terms
    - material type
    - sample type
    - experiment type
    - data set type

 

Please note that this role cannot be assigned via the ELN UI, only via admin UI.
