---
layout: page
title: Database publication
permalink: /db_publication/
show_sidebar: false
menubar: menu
toc: true
toc_title:  Database publication
hero_height: is-small
---
Graphic user interfaces (GUIs)

As we saw in 3.1 databases can be accessed through user interfaces. 
We can now add that there can be different interfaces responding to different needs. MySQL Workbench, for example, is a good interface to create a database,
 and to query it. Inserting data, however, and browsing it can be more easily done through dedicated interfaces that allow us to gather the data which is spread across different tables 
 and to visualise it in a different and more functional way. Some RDBMS such as Microsoft Access or Filemaker allow the users to build such interfaces
  (e.g. Microsoft Access or Filemaker) or they can be provided by dedicated software (such as Forest Admin or Draxlr). In Trismegistos, for example,
   while it relies on a MySQL database to provide data to its online interface, data is entered through a set of GUIs created with Filemaker. 
   The data is then exported from the Filemaker database to the MySQL database. In DAMOS, which relies on a MariaDB relational database, data have in the past been entered also using an interface built with Microsoft Access and directly connected to the MariaDB database, alongside with the use of the MySQL Workbench GUI. More recently, however, a system to import/export the data (i.e., the Mycenaean texts with their metadata) as EpiDoc compliant XML files is being developed. The aim or this system is to benefit from an advantage of working with XML databases, where a convenient interface is already provided by the XML document itself, which constitutes the basic unit of such databases and can be directly edited by users. The Papyrological Editor of Papyri.info, however, which allows users to enter and modify data using Leiden+ and then converts it to EpiDoc, constitutes an additional interface created to further ease the work on creating an editing XML files of papyrus texts (see Unit II).

As we know, Papyri.info provides also a Papyrological Navigator, which is an example of a GUI created to allow users to query and visualise data and metadata contained in the different databases which contribute to Papyri.info (on the structure of papyri.info see Unit II and unit IV on LOD). Websites such as Papyri.info and Trismegistos, which are connected to databases and through which we can query and visualise their data, are called dynamic websites, because the information they display is not entirely predefined, but it is determined by the queries of the users. Most of the online corpora listed in 3.3 are dynamic websites, but John Younger’s Linear A online corpus, a pioneering project, is an example of a static website, i.e., a website which is entirely precompiled and stored as HTML files (HTML is the markup language used to structure web pages). A static website has limited search possibilities, basically limited to text searches. Publishing a collection of inscriptions in a static website might sometimes be a good choice for individual projects and for disseminations, but the existence of tools as EFES (see 1.3.4), which facilitates the publication online of collections of XML documents, makes this an almost equally easy choice.

## Static websites

Creating a publication using EFES or creating a static website does not necessarily require advanced programming knowledge. It does, however, of course require some learning and to this end there are good online lessons, such as those offered by Programming historian or the Carpentries on creating static websites.

Programming historian: Building a static website with Jekyll and GitHub Pages

Carpentries: Building Websites With Jekyll and GitHub (beta version)

## Dynamic websites
Creating a dynamic website requires a certain amount of programming knowledge, usually including:

- HTML
- CSS, used to describing the presentation, i.e., the appearance of a web page
- JavaScript, used to make web pages dynamic and interactive
- PHP, Python or XSLT (in the case of XML databases) used to connect the web page to the database and, 
through the incorporation of queries written in SQL (in the case of relational databases) or XQuery (in the case of XML databases), to fetch data from the database.

Good tutorials and learning material are available online at:

Programming Historian: Understanding Web Pages and HTML

TutorialRepublic: https://www.tutorialrepublic.com/

W3Schools: https://www.w3schools.com/howto/howto_make_a_website.asp

However, as already mentioned, the amount of information and skills to learn before being able to create good dynamic interfaces is quite extensive.

Even though online interfaces are usually the most user-friendly solution for querying a database, it should be kept in mind that hardly any interface can offer all the (advanced) querying possibilities allowed by directly querying the database using a query language, be it XQuery or SQL. So, it is worth keeping in mind that knowing how to build SQL queries in the command line which is incorporated in tools such as MySQL Workbench or how to use XQuery in eXist, can be extremely useful for a student or a researcher. SQL queries are, as already mentioned, also particularly useful for advanced manipulation of data in a relational database.

Finally, graphical user interfaces do not only require to be built using programming languages, but also require to be designed. Designing an interface, so that it can be functional and  fit different users’ needs, is a separate process from its construction and it can benefit from design theory and techniques (see 3.2.1).
Visualisation and exploration tools

Ad hoc interfaces are not the only way to visualise data from a database. Several off-the shelf tools exist which can be used to this end. These include platforms such as MediaWiki, the platform used to publish Wikipedia, Datasette and Omeka, which can be used to produce digital exhibitions with a number of search functionalities, Gephi and NoadGoat, both of which can be used to create graphs or do statistical analysis. RStudio is a platform to perform statistical analyses and visualise data using the popular programming language R. Both Programming historian and the Carpentries offer introductory courses in R.

External tutorials:

Programming Historian: Up and Running with Omeka.net

Programming Historian: R Basics with Tabular Data

The Carpentries: Programming with R