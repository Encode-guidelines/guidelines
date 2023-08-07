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
The first decision in the creation of a database is that of the database management system and the data model. Three groups are widely used, with different advantages and disadvantages depending on the characteristics of the data and the planned application of the database: 
### 1. Relational databases:
Relational databases, such as SQL databases provide high data consistency, standardization and low redundancy. However, the tabular schema does not apply well to all data (e.g. texts) and structures (e.g. hierarchical). [trismegistos.org](trismegistos.org) is based on a relational database.
### 2. document-oriented databases:
In the field of papyrology and epigraphy, XML databases are the most widely used document-oriented databases. The advantage is flexibility and horizontal scalability. An example is the data underlying [papyri.info](www.papyri.info).
### 3. Graph databases:
The strength of graph databases lies in the mapping of hierarchical and networked structures and complex queries. A prominent representative is the Resource Description Framework (RDF), which plays an important role for the Semantic Web and Linked Open Data (LOD). An introduction to RDF and LOD was given at the [Encode Training Event on May 26-28, 2021](https://site.unibo.it/encode/en/encode-project-conference-programme-201ebridging-the-gap-with-linked-open-data201c-25th-may-2021-1.pdf/@@download/file/Invitation-ENCODE%20Intensive%20Training%2026th%20to%2028th%20May%202021.pdf).

## Creating a text corpus and database
### EpiDoc
The simplest way to create a corpus of papyrological or epigraphic texts is to encode the texts in [EpiDoc](https://epidoc.stoa.org/), a subset of [TEI XML](tei-c.org) developed specifically for ancient documents. In this process, each text is encoded in a separate file; the [EpiDoc Guidelines](https://epidoc.stoa.org/gl/latest/) introduce the structure of the file and provide an introduction to the encoding.
Files encoded in this way can then be published and made searchable online using the [EpiDoc Front-End Services (EFES)](https://github.com/EpiDoc/EFES) without in-depth IT knowledge. Those who want to develop complex queries themselves can search, manipulate and publish the files with [eXist-db](http://exist-db.org/) using [XQuery](https://www.w3schools.com/xml/xquery_intro.asp).
