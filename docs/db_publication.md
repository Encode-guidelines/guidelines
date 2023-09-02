---
layout: page
title: Publication
permalink: /db_publication/
show_sidebar: false
menubar: menu
toc: true
toc_title:  Publication
hero_height: is-small
---

The publication of a database could be said to happen when its content is stored and made available on an open repository 
(see [2.1.2](/db_share_store)). However, most often, *publication* would mean make it available through an online Graphic User Interface (GUI).

## Graphic User Interfaces

See also [3.1.1](https://teach-dariah-cur.acdh-dev.oeaw.ac.at/mod/lesson/view.php?id=2503) of the ENCODE Online Course

### Static Websites

A static website has limited search possibilities, basically limited to text searches. Publishing a collection of inscriptions in a static 
website might sometimes be a good choice for individual projects and for disseminations, but the existence of tools as EFES (see 1.3.4), 
which facilitates the publication online of collections of XML documents, makes this an almost equally easy choice.
Creating a publication using EFES or creating a static website does not necessarily require advanced programming knowledge. 
It does, however, of course require some learning and to this end there are good online lessons, such as those offered by 
Programming historian or the Carpentries on creating static websites.
Programming historian: Building a static website with Jekyll and GitHub Pages

Carpentries: Building Websites With Jekyll and GitHub (beta version)

(https://carpentries-incubator.github.io/jekyll-pages-novice/)

### EFES

EFES, in particular, is a customisable platform specifically designed to publish ancient texts in EpiDoc XML, 
allowing the creation of multiple indices, search and browse interface, concordances, and integration with linked open data. 
Many of the epigraphic projects mentioned in the previous chapters are published via EFES; for a list of projects based on 
EFES: https://github.com/EpiDoc/EFES/wiki/Projects-using-EFES.

### Dynamic Websites

Tutorials for creating websites can be found at:
- [W3Schools](https://www.w3schools.com/): [How TO - Build a Website](https://www.w3schools.com/howto/howto_website.asp) 
- [TutorialRepublic](https://www.tutorialrepublic.com/): [Learn How to Make a Website](https://www.tutorialrepublic.com/)

A general introduction can be found at the [Programming Historian](/prog_hist):  
- [Understanding Web Pages and HTML](https://programminghistorian.org/en/lessons/viewing-html-files)

Creating a dynamic website requires a certain amount of programming knowledge, usually including:

- HTML (HyperText Markup Language), the standard markup language used to create documents with the content of a web page  
[W3Schools](https://www.w3schools.com/html/default.asp) | [Tutorial Republic](https://www.tutorialrepublic.com/html-tutorial/)
- CSS, used to describe the presentation, i.e., the appearance of a web page  
[W3Schools](https://www.w3schools.com/w3css/default.asp)  | [Tutorial Republic](https://www.tutorialrepublic.com/css-tutorial/)
- JavaScript, used to make web pages dynamic and interactive  
[W3Schools](https://www.w3schools.com/js/default.asp)  | [Tutorial Republic](https://www.tutorialrepublic.com/javascript-tutorial/)
- PHP, Python or XSLT (in the case of XML databases) used to connect a web page to a database and, through the incorporation
 of queries written in an appropriate programming language, to fetch data from the database.  
 PHP: [W3Schools](https://www.w3schools.com/php/default.asp) | [Tutorial Republic](https://www.tutorialrepublic.com/php-tutorial/)  
 Python: [W3Schools](https://www.w3schools.com/python/default.asp)  
 XSLT:  [W3Schools](https://www.w3schools.com/xml/xsl_intro.asp)
- SQL (in the case of relational databases), XQuery or XPath (in the case of XML databases), used to write the queries to
 to fetch data from the database  
 SQL:[W3Schools](https://www.tutorialrepublic.com/sql-tutorial/)  | [Tutorial Republic](https://www.tutorialrepublic.com/sql-tutorial/)  
 XQuery:[W3Schools](https://www.w3schools.com/xml/xquery_intro.asp)   
XPath:[W3Schools](https://www.w3schools.com/xml/xpath_intro.asp) 



### Other Visualization Tools
Ad hoc interfaces are not the only way to visualise data from a database. 
Several off-the shelf tools exist which can be used to this end. 
These include platforms such as MediaWiki, the platform used to publish Wikipedia, Datasette and Omeka, 
which can be used to produce digital exhibitions with a number of search functionalities, Gephi and NoadGoat, 
both of which can be used to create graphs or do statistical analysis. RStudio is a platform to perform statistical analyses and 
visualise data using the popular programming language R. Both Programming historian and the Carpentries offer introductory courses in R.

External tutorials:

Programming Historian: Up and Running with Omeka.net

Programming Historian: R Basics with Tabular Data

The Carpentries: Programming with R

