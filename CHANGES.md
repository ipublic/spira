# Changelog for Spira <http://github.com/datagraph/spira>


## 0.0.2
 * Implemented #each on resource classes, allowing classes with a defined RDF
   type to be enumerated
 * Fragment URIs are now used as strings, allowing i.e. Integers to be used as
   the final portion of a URI for classes with a base_uri defined.
 * Added an RDF::URI property type
 * Implemented #to_rdf and #to_uri for increased compatibility with the RDF.rb 
   ecosystem

## 0.0.1
 * Initial release