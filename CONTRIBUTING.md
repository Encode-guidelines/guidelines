---
layout: page
title: Contributing
permalink: /contributing/
show_sidebar: false
menubar: menu
toc: true
toc_title: CONTRIBUTING
hero_height: is-small
---

# How to Contribute To The Encode Guidelines

## Format:

you have various possibilities:

1. add  a markdown (.md) file to the folder [docs](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs).
   To create a markdown file, create a .txt file and then change the file extension to *.md*.
   
   If you add the following (including the \--- at the beginning and at the end):  

   \---  
   layout: page  
   title: *add-a-title*  
   permalink: */add-a-one-word-title/*  
   show_sidebar: false  
   menubar: menu  
   toc: true  
   toc_title: *add-a-table-of-content-title*  
   hero_height: is-small  
   \---  

   to the top of your document and substitute the parts in *italics* (but don't write them in *italics* in the document), you will be able to see it
   in the [Guidelines website](https://encode-guidelines.github.io/guidelines/), by typing https://encode-guidelines.github.io/guidelines/the-one-word-title-you-added/ in your browser (you can also open the present page in GitHub and take its top part as an example).

   [Here:](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) you'll find instructions on how to write in markdown in GitHub. A more comprehensive reference is to be found [here] (https://www.markdownguide.org/).

   NB!: section titles that you want to appear in the page's Table of Content (see, e.g. the [EpiDoc page in these Guidelines](https://encode-guidelines.github.io/guidelines/epidoc/)) of the webpage need to be preceded by ## or ### (for subtitles).

   **Remember that changes may take up to 10 minutes to show up in the [online version of the Guidelines](https://encode-guidelines.github.io/guidelines/)**
   
2. edit a .md file already present in the folder [docs](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs)

   please, do not change anything between the two "---" on the top of the page of existing .md documents, as it would result in changes/errors in the
   [Guidelines website](https://encode-guidelines.github.io/guidelines/).

   Again: remember that changes may take up to 10 minutes to show up in the [online version of the Guidelines](https://encode-guidelines.github.i
   /guidelines/)
 
 3. if you wish to write with Microsoft Word, you can afterwards convert it to Markdown using the [Pandoc software](https://pandoc.org/).
    NB!: Pandoc does not have a graphic interface, so you will have to use Terminal on Mac or Command Prompt on Windows, but the Pandoc website guides
    you nicely through [all the necessary steps](https://pandoc.org/getting-started.html)
 
 4. you can also put Word documents in the [ENCODE common drive](https://drive.google.com/drive/folders/1zrehnzzbwKl4cjvHnlZ1MhNbF_Xt4Ym7) and then it
    will be converted by the current editor of the Guidelines (currently after the 7/8).

## Content:

The ENCODE guidelines are conceived as a companion resource to the ENCODE open online course, published ond DARIAH teach, and to the ENCODE Database. They are conceived as a more dynamic and updated reference resource, presenting a more systematic list of resources for digital methodes in the study of ancient writing cultures and for the learning and teaching of them. The educational focus is the distinctive character of this resource, as it was of the [ENCODE project](https://site.unibo.it/encode/en), which constitutes their background.
Resources are here presented which teachers and learners approaching digital methodes in the study of ancient writing cultures should become familiar with or, at the very least, know the existence of. 

### Structure

Resources have been divided in the following sections, reflected by the structure of the website:

##Corpus and database creation: resources are listed which are useful to create, work with, store, publish and disseminate databases (with particular regard for the creation of textual corpora of ancient languages). At the moment it comprises the following pages/documents:

- [Creation](https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/corpus_db.md)
- [Publication](https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/db_publication.md)
- [Storing & sharing](https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/db_share_store.md)
- [Sharing with LOD](https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/lod.md)
  
Resource descriptions can be inserted into the current markdown documents or uploaded as Word files as describe in point 2 and 4 [above](https://github.com/Encode-guidelines/guidelines/edit/gh-pages/CONTRIBUTING.md#format).

##Best practices: links to guidelines, user manuals and best practices summaries

Resource descriptions can be uploaded as markdown documents in the [docs folder](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs) or uploaded as Word files as describe in point 1 and 4 [above](https://github.com/Encode-guidelines/guidelines/edit/gh-pages/CONTRIBUTING.md#format)

##Courses: resources offering open access lessons and courses about relevant themes

Resource descriptions can be uploaded as markdown documents in the [docs folder](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs) or uploaded as Word files as describe in point 1 and 4 [above](https://github.com/Encode-guidelines/guidelines/edit/gh-pages/CONTRIBUTING.md#f

##Portals and mailing lists: relevant sites such as 

Resource descriptions can be uploaded as markdown documents in the [docs folder](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs) or uploaded as Word files as describe in point 1 and 4 [above](https://github.com/Encode-guidelines/guidelines/edit/gh-pages/CONTRIBUTING.md#f

##Bibliographies: relevant online bibliographies such as [Doing Digital Humanities - A DARIAH Bibliography](https://www.zotero.org/groups/113737/doing_digital_humanities_-_a_dariah_bibliography) or the [BIBLIOGRAPHIE PAPYROLOGIQUE
EN LIGNE](http://www.aere-egke.be/BP/):

https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/biblio.md

Resource descriptions can be uploaded as markdown documents in the [docs folder](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs) or uploaded as Word files as describe in point 1 and 4 [above](https://github.com/Encode-guidelines/guidelines/edit/gh-pages/CONTRIBUTING.md#f

The site is completed by:

- an **introduction** about:

 - the Encode project

 - the present Guidelines
   https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/competences.md

 - the ENCODE database and its pedagogical frame:
   https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/competences.md

- a list of relevant (either present in the Mooc or relevant in general) terms and concepts will appear, with short and simple definitions, in the section **Terminology**. To contribute to the list, either by proposing a term or (even better!) a term and a definition, please just add them to the document [terminology.md](https://github.com/Encode-guidelines/guidelines/blob/gh-pages/docs/terminology.md ) in the [docs](https://github.com/Encode-guidelines/guidelines/tree/gh-pages/docs) folder.
