# Vocabulary Processing Scripts
Use these scripts to preprocess vocabularies for use with Google Refine's
[RDF reconciliation tool](http://lab.linkeddata.deri.ie/2010/grefine-rdf-extension/).
The scripts are demonstrated in the JASIST article
[&ldquo;Evaluating the success of vocabulary reconciliation for cultural heritage collections&rdquo;](http://freeyourmetadata.org/publications/freeyourmetadata.pdf).

## Level of depth
- `findlevel` calculates the level of depth for a hierarchy of SKOS concepts
- `addlevel` adds the level of depth to a collection

## Preprocessing
- `uniquify_labels` outputs prefLabels and altLabels such that there are no duplicates

## XML tools
- `xml_outline` generates a visual outline of an XML document
- `aat_to_turtle` converts an XML representation of the Art & Architecture Thesaurus (AAT) to Turtle
