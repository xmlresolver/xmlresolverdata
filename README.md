# XML Resolver Data

The standard DTDs, schemas, and URIs that ship with the XML Resolver.

This repository contains the data files that are packaged up with the resolver.

For the Java release, these files and an associated catalog are in the
`xmlresolver` jar file with the `data` classifier.

For the C# release, these files and an associated catalog are in the
`XmlResolverData` assembly.

This repository is used as a subproject in the Java and C# repositories.

## Change Log

### October 2024

* Added XML DSig schemas. Thanks @dizzz

### January 2024

* Corrected an incorrect public identifier for `https://www.w3.org/2001/datatypes.dtd` in
  the manifest.
* Corrected the system identifiers for the XML Catalogs V1.1 DTD. (They were incorrectly
  recorded as `uri` elements in the manifest where `system` was required.)
* Bumped version to 6.0.0 to align with the refactored Java and C# resolvers
