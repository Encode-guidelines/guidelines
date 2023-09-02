---
layout: page
title: Database storing & sharing
permalink: /db_share_store/
show_sidebar: false
menubar: menu
toc: true
toc_title: Database storing & sharing
hero_height: is-small
---

## Storing & Sharing

Databases can of course be stored on a private computer. This is, however, not the best solution from the  sustainability point of view.
In order to comply with [FAIR principles](https://www.go-fair.org/fair-principles/), according to which scientific data should be
 *findable*, *accessible*, *interoperable* and *reproducible* a database should be stored in an open access repository, together with a
  description of its content and structure. Further, its content should ideally be downloadable in different file formats.

### Export
Different  [types of database](/db_creation/) 
(see also [Unit 3 of the ENCODE Online Course](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/mod/lesson/view.php?id=2503)) 
can be exported and stored in different file format:

- single files (called **.sql files** in the case of SQL databases), which, when launched with the right software (a RDBMS), 
wil recreate the database.

- as a multi-file dataset, for example using the CSV (Comma Separated Values) format. In the case of XML databases, these would obviously a collection of XML files. 
These files can then be reused independently or imported in a database structure to recreate the original database.

As mentioned, a dataset should always include a file describing the structure of the data and its content, since these are usually not self-explanatory 
(think for example of column names or the relationships between tables in a relational database).

### Repositories
In addition to national or institutional (e.g. maintained by universities) repositories, the following are frequently used by researchers in the Humanities:

- [GitHub](https://github.com/):  
is one of the most used open platforms for software development, where to store, share and manage code. Collaboration is made easy by the [Git](https://git-scm.com/) 
versioning system.
GitHub is also widely used by the Digital Classics community (e.g. [Sunoikisis DC](https://github.com/SunoikisisDC), 
[ENCODE](https://github.com/Encode-guidelines), [Epigraphy.info](https://github.com/epigraphy-info)) for storing and sharing documents and datasets.  
Although owned by Microsoft since 2018 it remained a free and open platform.

- [Zenodo](https://zenodo.org/):  
a general-purpose, free and open repository developed under the [OpenAIRE](https://www.openaire.eu/)non-profit partnership, as a part of a program 
to ensure a permanent open scholarly communication infrastructure to support European research.
Zenodo is permanently stored at CERN’s Data Centre and is thus an ideal place for long time storing.  Every upload is  given a Digital Object Identifier (DOI) and is, 
thus, easily citable. Zenodo allows versioning and integration with GitHub. Finally, it also offers usage statistics. See for example the
 [Digital Classics community's library](https://zenodo.org/communities/digiclass/)


Finally, it should be remarked tha that planning how to the store and share data should always be a part of planning of a database. 
This is also usually demanded in funding applications.