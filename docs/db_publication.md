---
layout: page
title: Building a Corpus > Publication
permalink: /db_publication/
show_sidebar: false
menubar: menu
toc: true
toc_title:  Building a Corpus > Publication
hero_height: is-small
hero_image: guidelines/images/gortyna.jpg
---

## Publication through a Graphic User Interfaces
The publication of a database could be said to happen when its content is stored and made available on an open repository 
(see [2.1.2](/db_share_store)). However, most often, *publication* would mean to make it available through an online Graphic User
 Interface (GUI), that is website that allows users to interact (search and query) a database in a way that is relatively intuitive, 
 without the need to know programming languages. (See also [3.1.1](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/mod/lesson/view.php?id=2503) of the 
 ENCODE Online Course)

### Static Websites

Websites can be static or dynamic. In static websites  the information displayed is entirely predefined and contained in HTML documents and 
can be searched using textual searches. Dynamic websites, on the other hand, can be connected to a database and allow users to query it. 

Static websites are thus not ideal for the publication of a big corpus, but can be used for small projects and for dissemination.
Their advantage is that they are relatively easy to create and maintain.

A tutorial for creating a static website can be found at:
- [W3Schools](https://www.w3schools.com/): 
[How TO - Make a Static Website](https://www.w3schools.com/howto/howto_website_static.asp) 

The [GitHub](https://github.com/) platform (see [2.1.2](/db_share_store/#repositories)) allows to publish the content of the repository 
through the [GitHub Pages](https://pages.github.com/) infrastructure.

A combination of the following lessons gives a useful introduction on creating a static website starting from a GitHub repository:  

- **[Programming historian](/prog_hist)**:
[Building a static website with Jekyll and GitHub Pages](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages)
  
- **[The Carpentries](soft_carp)**: 
[Building Websites With Jekyll and GitHub (beta version)](https://carpentries-incubator.github.io/jekyll-pages-novice/)

### EFES

EpiDoc Front-End Services, [EFES](https://github.com/EpiDoc/EFES) is a free customizable platform specifically designed 
to publish collection of texts in EpiDoc XML. It allows the creation of indices, a search and browse interface, concordances, 
and integration with linked open data. See: [2.1.1](/db_creation/#epidoc).

### Dynamic Websites

The best way to publish online the content of a database is through a dynamic website, which allows users to interact with and query the 
content of the database. 

Creating a dynamic website requires a certain amount of programming knowledge, usually including:

- **HTML** (HyperText Markup Language), the standard markup language used to create documents with the content of a web page  
[W3Schools](https://www.w3schools.com/html/default.asp) | [Tutorial Republic](https://www.tutorialrepublic.com/html-tutorial/)
-  **CSS**, used to describe the presentation, i.e., the appearance of a web page  
[W3Schools](https://www.w3schools.com/w3css/default.asp)  | [Tutorial Republic](https://www.tutorialrepublic.com/css-tutorial/)
-  **JavaScript**, used to make web pages dynamic and interactive  
[W3Schools](https://www.w3schools.com/js/default.asp)  | [Tutorial Republic](https://www.tutorialrepublic.com/javascript-tutorial/)
-  **PHP**,  **Python** or  **XSLT** (in the case of XML databases) used to connect a web page to a database and, through the incorporation
 of queries written in an appropriate programming language, to fetch data from the database.  
 PHP: [W3Schools](https://www.w3schools.com/php/default.asp) | [Tutorial Republic](https://www.tutorialrepublic.com/php-tutorial/)  
 Python: [W3Schools](https://www.w3schools.com/python/default.asp)  
 XSLT:  [W3Schools](https://www.w3schools.com/xml/xsl_intro.asp)
-  **SQL** (in the case of relational databases),  **XQuery** or **XPath** (in the case of XML databases), used to write the queries to
 to fetch data from the database  
 SQL:[W3Schools](https://www.tutorialrepublic.com/sql-tutorial/)  | [Tutorial Republic](https://www.tutorialrepublic.com/sql-tutorial/)  
 XQuery:[W3Schools](https://www.w3schools.com/xml/xquery_intro.asp)   
XPath:[W3Schools](https://www.w3schools.com/xml/xpath_intro.asp) 

Tutorials for creating dynamic websites can be found at:
- [W3Schools](https://www.w3schools.com/): [How TO - Build a Website](https://www.w3schools.com/howto/howto_website.asp) 
- [TutorialRepublic](https://www.tutorialrepublic.com/): [Learn How to Make a Website](https://www.tutorialrepublic.com/)

A general introduction can be found at the [Programming Historian](/prog_hist):  
- [Understanding Web Pages and HTML](https://programminghistorian.org/en/lessons/viewing-html-files)

## Other Visualization Tools 
Data from a database can also be visualized through already existing, off-the shelf tools. Here is a selection of them:
 
- [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki)
- [Datasette](https://datasette.io/)
- [Omeka](https://omeka.org/)  
   See: [Programming Historian](/prog_hist):
[Up and Running with Omeka.net](https://programminghistorian.org/en/lessons/up-and-running-with-omeka)
- [Gephi](https://gephi.org/)
- [NoadGoat](https://nodegoat.net/)
- [Rtudio](https://posit.co/)  
  See: [Programming Historian](/prog_hist): [R Basics with Tabular Data](https://programminghistorian.org/en/lessons/r-basics-with-tabular-data)  | 
[The Carpentries](soft_carp): [Programming with R](https://swcarpentry.github.io/r-novice-inflammation/)







