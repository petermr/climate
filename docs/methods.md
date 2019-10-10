# Methods

Table of Contents

 - Dictionaries

## Dictionaries creation process (method)

The dictionaries being made for use with OCK are 'exploratory dictionaries'.

Terms used in the dictionaries are from Wikidata (if they don't exist in Wikidata we will add them).

The dictionaries are used to search for documents and to classify them. For example if two documents share a dictionary term then the documents can be used in the following ways:

- have machine learning applied,
- have information annotated, or
- be related to authoritative community such as Wikidata from where we are linking the dictionary terms

### An Example dictionary for 'runaway climate change'

https://github.com/petermr/climate/blob/master/dictionary/runaway.xml

An early example which can then be built on with searches etc.

 - acceleration 
 - anthropogenic
 - feedback 
 - forcing 
 - model 
 - sea ice 
 - atmospheric 
 - insolation 
 - agricultural 
 - anthropocene 
 - ipcc 
 - carbon cycle 
 - arctic 
 - antarctic 

### How are the terms selected

 1. Look at what exists in a field.
 2. Collect what exists in papers, reports, and academic literature.
 3. Check these terms against believable collections of terms, e.g., Wikipedia categories, and Wikidata terms.
 4. Check the terms against an authority such as IPCC.

It is important to note that openNotebook displays a number of statistics and analysis of the documents search which can be viewed in the downloaded repository, such as term frequency, etc. These can be used to find and select terms to be used.

https://github.com/petermr/climate/blob/master/searches/runaway203/full.dataTables.html

Also note that the terms from Wikidata use the term IDs and that way they can function across multiple languages as long as equivalent terms are entered where needed for other languages.
