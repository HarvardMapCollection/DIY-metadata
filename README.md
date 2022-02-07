# DIY-metadata

Government portals, libraries, and other data repositories often use slightly different metadata standards for powering discovery of their data resources.

If you are creating your own data, or reshaping data you have found so it is easier to work with for some purpose, you might not always know the exact contextual information to provide so the data can be the most widely discovered, understood, and used.

This guide provides a template for creating documentation for GIS data projects that well-positions them for discovery and use.

## Tips

- Document your data creation and editing process early and often. It is much easier to write down what you do as you're doing it than to try to remember afterwards.
- Write your documentation in open formats, such as .txt. Avoid proprietary formats such as Microsoft Word files to extend the longevity and accessibility of your work.
- Incomplete context is *always* better than no context. If you don't know the answers to everything included in this template, just try to populate as much as you can.
- Share! Upload your data resources, codebooks, scripts, and documentation to Github, Dataverse, or OSF if immediate ingest into a geo-portal is not an option. Link to these well-contextualized data materials from any digital project making use of the data. 

## Documentation elements

**Originator(s):** the name(s) of the organization(s) or individual(s) that developed the data set. 

**Publication Date:** the date when the data set is published or otherwise made available for release. 

**Title:** the name by which the dataset is known. 

**Geospatial Data Presentation Form:** the mode in which the geospatial data are represented. 

**Abstract:** a brief narrative description of the data set. 

**Purpose:** the reason why the dataset was developed or intentions for its use. 
If you created the data yourself, or augmented existing data, how does the work add value to the current data landscape. In other words, what are the project's successes?

**Process steps and methods:** a sequential explanation of the step-by-step process for creating or editing the data.

**Challenges:** challenging aspects of working with the data, or words-to-the-wise for someone else endeavoring to work with it. 


**Currentness Reference of the Content:** a description of how the content date was determined, i.e. publication date or ground condition. 

**Calendar Date(s) of the Content:** the date, dates or date range describing the content of the dataset. 

**Maintenance and Update Frequency:** schedule for updating or maintaining the data layers. 

**Bounding Coordinates:** the minimum and maximum latitude and longitude coordinates of the dataset expressed in decimal degrees. 
> These can often be [auto-calculated using GIS software](https://gis.stackexchange.com/questions/85192/getting-extent-of-layer-in-qgis).

**Theme Keyword(s):** common-use word or phrase used to describe the subject of the data set. 

**Theme Keyword Thesaurus:** the formally registered thesaurus or a similar authoritative source of theme keywords from which the theme keywords were selected, for example, [Library of Congress subject headings](https://id.loc.gov/authorities/subjects.html). 

**Place Keyword(s):** the geographic name of a location covered by a data set. 
> You can use a thesaurus such as [geonames.org](http://www.geonames.org/).

**Place Keyword Thesaurus:** the formally registered thesaurus or a similar authoritative source of place keywords from which the place keywords were selected. 

**Access Constraints:** restrictions on access to the data. 

**Use Constraints:** restrictions on the use of the data. 

**Point of contact:** contact information for an individual or organization that is knowledgeable about the data set [person/organization, address, phone, e-mail, etc.]. 

**Data sources:** If you obtained data from elsewhere and edited it, the source of the original datasets and date accessed.

**Projection:** The EPSG code for the data's projection.
> Example: EPSG: 4326. 

**Relationships:** If there are multiple datasets in the project, processing scripts, or other resources, the filenames and how the materials relate to or were used with one another.

**Data integrity:** If values are missing, or fields are blank, instructions for future users on how to make sense of why.

**Codebooks:** If you cleaned data, deleted, renamed, mathematically calculated or inferred fields from other fields, the filename and link to a plain-text codebook with field name definitions, including units of measurement.




