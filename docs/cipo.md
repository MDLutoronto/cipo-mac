---
title: "Canadian Intellectual Property Office (CIPO) Patent PostgreSQL Database"
layout: "home"
description: "This tutorial will help you get up and running querying the Canadian Intellectual Property Office (CIPO) Patent PostgreSQL Database. It will cover accessing the high performance computing environment, querying the database via SQL statements and from within a python script, and downloading the results of the query. You will need a Compute Canada account with the proper credentials to access this database. If you haven’t done so already, you should first follow the instructions to get your account set up."
staff:
    - name: Kara Handren
      link: https://library.utoronto.ca/staff/kara-handren 
maintainer:
    - name: Leslie Barnes
      link: https://library.utoronto.ca/staff/leslie-barnes
created_date: 2023-01-05
permalink: "/"  #! Remove this if not the homepage
nav_order: 0
has_children: true
has_toc: false
---
# Canadian Intellectual Property Office (CIPO) Patent PostgreSQL Database
The **Canadian Intellectual Property Office (CIPO) Patent PostgreSQL Database** is a metadata extract from CIPO's [IP Horizon's XML Databank](https://ised-isde.canada.ca/site/canadian-intellectual-property-office/en/patent-data-bibliographic-and-full-text-xml) that contains information on over 2.5 million patent documents filed in Canada. Data are available from 1870 to present, and include metadata as well as the full text of patent descriptions and claims information. These documents represent both patent applications and patent grants, as well as patents that have expired. Many patents provide references to equivalent patents filed in other countries, via the World Intellectual Property Office's (WIPO) Patent Cooperation Treaty (PCT).

This XML has been converted into an object-relational database (updated annually) and is available to UofT faculty, staff, and students for querying in a high performance computing environment offered by [SciNet](https://www.scinethpc.ca/). Currently the database contains data up to and including July 23, 2023.

This is an excellent dataset for use in text and data mining research. It can be programmatically queried via SQL statements directly or through python scripts, with no limits on query results.

## Restrictions
While CIPO's XML files are available openly via [IP Horizons](http://ised-isde.canada.ca/site/canadian-intellectual-property-office/en/patent-data-bibliographic-and-full-text-xml), this PostgreSQL database is intended for academic study, research, teaching and administrative use at the University of Toronto. Access to the database is restricted to University of Toronto faculty, students, researchers and staff. 

## Access
In order to access the database, you must first gain access to the high performance computing environment through a [multi-step process](https://mdlutoronto.github.io/postgresql-databases-access/) to create the appropriate account (may take a few days to create the account initially).

## Working with the Database
You query the database using SQL statements, and then can either continue to work with the results within this computing environment, or download the results as a CSV file.

* [This document](https://maps.library.utoronto.ca/docs/postgresql/CIPO/db-structure.pdf) describes the various tables and their contents and can help you when constructing your SQL statements.
* This [Entity Relationship Diagram (ERD)](http://maps.library.utoronto.ca/docs/postgresql/CIPO/CIPO_ERD.pdf) provides a visual representation of all of the tables within the database and their relationships.

## Help
If working with object-relational databases, SQL, and/or high performance computing environments are new to you, check out the following tutorials.

If you have any question, feel free to [contact us](https://mdl.library.utoronto.ca/about/contact-form).

**Technique:** [Searching for maps and data](https://mdlutoronto.github.io/tutorials-search/?technique=Searching+for+maps+and+data), [Text and Data Mining](https://mdlutoronto.github.io/tutorials-search/?technique=Text+and+Data+Mining) \| **Tools:** [CIPO](https://mdlutoronto.github.io/tutorials-search/?tool=CIPO)