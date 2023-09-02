---
layout: page
title: Creation
permalink: /db_creation/
show_sidebar: false
menubar: menu
toc: true
toc_title: Creation
hero_height: is-small
---
# Creating a corpus and database

## Database management system (DBMS)
The first decision in the creation of a database is that of the database management system and the data model. Three groups are widely used, with different advantages and disadvantages
depending on the characteristics of the data and the planned application of the database: 

### 1. Relational databases:
Relational databases, such as SQL databases provide high data consistency, standardization and low redundancy.
However, the tabular schema does not apply well to all data (e.g. texts with mark-up) 
and structures (e.g. hierarchical). [trismegistos.org](trismegistos.org) is based on a relational database. 
For further reading see Section [3.1.2 Relational databases](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/mod/lesson/view.php?id=2503&pageid=2528) of the ENCODE online course. 

### 2. Document-oriented databases:
In the field of papyrology and epigraphy, XML databases are the most widely used document-oriented databases. 
The advantages are flexibility (e.g. there is no need to define a schema upfront) and requires less transformations of the format of the data.
 An example is the data underlying [papyri.info](www.papyri.info). For further reading see Section [3.1.3 XML-databases](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/mod/lesson/view.php?id=2503&pageid=2530) 
of the ENCODE online course.

### 3. Graph databases:
The strength of graph databases lies in the mapping of hierarchical and networked structures and complex queries. 
A prominent representative is the Resource Description Framework (RDF), which plays an important role for the Semantic Web and 
Linked Open Data (LOD). An introduction to RDF and LOD was given at 
the [Encode Training Event on May 26-28, 2021](https://site.unibo.it/encode/en/encode-project-conference-programme-201ebridging-the-gap-with-linked-open-data201c-25th-may-2021-1.pdf/@@download/file/Invitation-ENCODE%20Intensive%20Training%2026th%20to%2028th%20May%202021.pdf), see our module [Linked Data and Ancient Documents](https://gn.biblhertz.it/encode/modules/m1)). A first introduction is in our [MOOC, Unit IV](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/course/view.php?id=73&section=7).

## Creating a text corpus and database
A more detailed overview is provided by Section [3.1 Database Infrastructures](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/mod/lesson/view.php?id=2503) of the ENCODE online course.
### EpiDoc
The simplest way to create a corpus of papyrological or epigraphic texts is to encode the texts in [EpiDoc](https://epidoc.stoa.org/), 
a subset of [TEI XML](tei-c.org) developed specifically for ancient documents. In this process, each text is encoded in a separate file; the [EpiDoc Guidelines](https://epidoc.stoa.org/gl/latest/) 
introduce the structure of the file and provide an introduction to the encoding.
Files encoded in this way can then be published and made searchable online using the [EpiDoc Front-End Services (EFES)](https://github.com/EpiDoc/EFES) without in-depth IT knowledge. 
Those who want to develop complex queries themselves can search, 
manipulate and publish the files with [eXist-db](http://exist-db.org/) using [XQuery](https://www.w3schools.com/xml/xquery_intro.asp).
