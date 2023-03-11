# LMSS
SALI LMSS: Legal Matter Standard Specification

The file LMSS.owl is an XML file that represents SALI's primary taxonomy/ontology, providing over 11,000 tags, each with its own unique identifier (IRI). 

The identifiers in this XML file are used in the SALI API standard, where stakeholders will use those identifiers/IRIs to send/receive API calls.

This LMSS.owl file will be updated regularly. But please note that until a formal Release (e.g., Version 3.0, Version 4.0), the commits are still subject to public review. They become final during the release. But even during the interim stages, any changes to the IRIs will be very, very unlikely.  In fact, nearly all of the IRIs will remain operative for decades (or forever). Changes (if any) are likely to be only with properties:
- E.g., Labels (i.e., `rdfs:label`)
- E.g., Synonyms (i.e., `skos:altLabel`) - translations to other languages
- E.g., Definitions
- E.g., Edges/relationships
- E.g., Multiple Parentage

The identifiers/IRIs themselves will remain static and stable.
