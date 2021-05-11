# Geonames data upload to SPARQL endpoint

Some documentation is here: https://www.geonames.org/ontology/documentation.html

Ontology is available here: https://www.geonames.org/ontology/ontology_v3.2.rdf


RDF dump is available here: https://download.geonames.org/all-geonames-rdf.zip

## instructions for uploading/updating the data:

- convert the data using the python script
- copy the geonames.nt file to the `/blazegraph` folder which is mapped to `/blazegraph-data/`
- go to the web UI of blazegraph, select the `update` tab and point to the file: `/blazegraph-data/geonames.nt`
- Select `update`
