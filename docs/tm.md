# Trismegistos Data Services User Guidelines

This guide provides information on how to effectively use the Trismegistos Data Services, designed for anyone interested in working with historical and geographical data from the ancient world.

## General Information

The Trismegistos Data Services portal is developed within the Linked Open Data framework of DARIAH-BE and CLARIAH-VL. All the data is available under a [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)

## Available Services

### [TexRelations Matcher](https://www.trismegistos.org/dataservices/api/doc/matchtext)

- The TexRelations Matcher is a cross-matching tool to find links to other projects with information about Ancient World texts.
- This API offers JSON, XML, and URI-based JSON responses.
- It helps you identify related records from 79 other projects using the TM Text ID or IDs from the TM partners.

### [GeoRelations Matcher](https://www.trismegistos.org/dataservices/api/doc/matchgeo)

- The GeoRelations Matcher is a tool with a similar principle as the TexRelations Matcher, but it helps you find place IDs from partner projects.
- This API offers JSON, XML, and URI-based JSON responses.
- Currently, links to 20 other projects are available.

### [GeoResponder](https://www.trismegistos.org/dataservices/api/doc/georesponder)

- This tool is perfect for those working with geographical data.
- It provides a GeoJSON response for the TM Geo ID, which is a standardized file format easily parseable in scripting languages such as Python and JavaScript.
- Be sure to check out the Memo on the RFC7946 GeoJSON format.

### [GeoRDF & RDF-extended](https://www.trismegistos.org/dataservices/rdf/geo/index.php)

- These services make TM Geo data available for linked data projects.
- There are two separate endpoints: [GeoRDF](https://www.trismegistos.org/dataservices/rdf/geo/index.php) and [RDF-extended](https://www.trismegistos.org/dataservices/rdf/geo/extended_index.php).
- Both endpoints take an argument ?id= followed by the TM Geo ID you're interested in.

### [Geo table dump](https://www.trismegistos.org/dataservices/api/doc/geotabledump)

- For large-scale projects that need a customized dump file of TM Places, we recommend using the Geographical data dump tool.
- Users can customize the response fields by simply checking the data they need and choose a CSV or JSON response format.

### [PerResponder](https://www.trismegistos.org/dataservices/api/doc/perresponder)

- This tool is useful for people working with prosopographical data.
- It will show you a JSON response for the TM Person ID you're looking for.

### [PerRDF](https://www.trismegistos.org/dataservices/rdf/per/index.php)

- We also developed an online endpoint to retrieve person-related data in the RDF format.
- The default data is available [here](https://www.trismegistos.org/dataservices/rdf/per/index.php).
- This endpoint takes one mandatory argument ?id= followed by the TM Per_ID you're interested in.

## How to Use Trismegistos Data Services

To effectively use the TM services, follow these steps:

1. **Choose the Service:** Select the service that suits your research needs. Each service serves a specific purpose, so choose accordingly.

2. **Request Data:** Make a request to the service using the provided endpoint. For some services, you can customize the response format.

3. **Interpret the Response:** The TM services will provide you with data in various formats. Carefully interpret the response according to your project requirements.

4. **Documentation:** For more detailed information and usage examples, refer to the documentation page of each endpoint. The documentation will help you make the most of these services.
