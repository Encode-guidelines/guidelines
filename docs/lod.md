---
layout: page
title: LOD
permalink: /lod/
show_sidebar: false
menubar: menu
toc: true
toc_title: LOD
hero_height: is-small
---

## LOD Guidelines

Linked Open Data (LOD) for the Semantic Web should follow these four general guidelines (proposed by Tim Berners-Lee):

### 1. Use URIs as names for things.
The Uniform Resource Identifier (URI) is a single global identification system used for giving unique names to anything – from digital content available on the Web to real-world objects and abstract concepts. With the help of URIs, we can distinguish between different things or know that one thing from one dataset is the same as another in a different dataset.

### 2. Use HTTP URIs so that people can look up these names.
As the HTTP protocol provides a simple mechanism for retrieving resources, when things can be identified by URIs in conjunction with this protocol, they become easier to find. This expedites publishing any kind of data and adding it to the global data space.

### 3. When someone looks up a URI, provide useful information, using the standards (RDF, SPARQL).
To be able to use URIs efficiently, we should use RDF or SPARQL for querying.

The RDF is a graph-based representation format for data publishing and interchange on the Web developed by the W3C. It is also used in semantic graph databases (also known as RDF triplestores) – a technology developed for storing interconnected data and inferring new facts out of existing ones.

SPARQL, on the other hand, is the W3C-standardized query language for retrieving and manipulating data stored in RDF format. As such, it allows us to search the Web of Data (or any database) and discover relationships.

### 4. Include links to other URIs so that they can discover more things.
Similarly to the hypertext web, links to other URIs makes data interconnected and enables us to find different things. By interlinking new information with existing resources, we maximize the reuse and interlinking among existing data and create a richly interconnected network of machine-processable meaning.

Berners-Lee also created a five-star scheme for LOD:

★	Available on the web (whatever format) but with an open licence, to be Open Data
★★	Available as machine-readable structured data (e.g. excel instead of image scan of a table)
★★★	as (2) plus non-proprietary format (e.g. CSV instead of excel)
★★★★	All the above plus, use open standards from W3C (RDF and SPARQL) to identify things, so that people can point at your stuff
★★★★★	All the above, plus: Link your data to other people’s data to provide context
 

## Publishing LOD

Publishing data as LOD could be done according to the following steps of the Linked Open Data life cycle:

### Data analysis
Analyze your data model, metadata and the data itself.

### Data cleaning
Make sure the data set you want to publish doesn't contain any redundant or unnecessary data.

### Data modelling
Choose established vocabularies and additional models to ensure a smooth data conversion to RDF. The next step is to create unified resource identifiers (URIs) as names for each of your objects. 

### Appropriate vocabularies
Evaluate appropriate RDF vocabularies for your data from existing ones. If there are no vocabularies that fit your needs, you can create your own.

### License choice
Provide clear licenses for unhindered data reuse, aligning with recognized standards (e.g., Creative Commons licenses).

### RDF Conversion
Convert your data into RDF format, choosing one or more of the serialization formats such as RDF/XML.

### Data interlinking
Link your data to other data sets to ensure optimised data processing and integration for data (re-)use. This will also allow for the creation of new knowledge from your data sets by putting them into a broader context with other data.

### LOD publishing and promoting
Make sure your Linked Open Data becomes Linked Open Usable Data (LOUD) by making your data set F(indable), A(ccessible), I(nteroperable) and R(eusable). You could for instance add your published data sets to the LOD cloud.


## Resources

W3C, 2014. Best Practices for Publishing Linked Data: [<u>https://www.w3.org/TR/ld-bp/</u>](https://www.w3.org/TR/ld-bp/)

W3C, 2014. The RDF Data Cube Vocabulary. [<u>https://www.w3.org/TR/vocab-data-cube/</u>](https://www.w3.org/TR/vocab-data-cube/)
 

## Bibliography

Berners-Lee, T. (2006) Linked Data. W3C. [<u>https://www.w3.org/DesignIssues/LinkedData.html </u>](https://www.w3.org/DesignIssues/LinkedData.html)
