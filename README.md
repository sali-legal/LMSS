# LMSS
SALI LMSS: Legal Matter Standard Specification

The file `LMSS.owl` is an XML file that represents SALI's primary taxonomy/ontology, providing over 11,000 tags.

## IRI = Unique Identifier
Each SALI LMSS tag has its own unique identifier (IRI). 

## SALI API standard uses IRIs as identifiers
The identifiers in this `LMSS.owl` file are used in the SALI API standard, where stakeholders will use those identifiers/IRIs to send/receive API calls.

## STABILITY AND VERSIONING
This `LMSS.owl` file will be updated regularly. 
- But please note that until a formal Release (e.g., Version 3.0, Version 4.0), the commits are still subject to public review. 
- The `LMSS.owl` will become final upon its Release. 
- Even during the interim stages (i.e., `main` branch, `develop` branch), changes to the IRIs will be unlikely. 
- Rarely, IRIs may be *deprecated* -- and then, most likely be related to consolidation/de-duplication (e.g., during the Public Comment stage). 
    - SALI will strive to retain deprecated IRIs -- placing them in a folder labeled `DEPRECATED NODES`. 

After a Release, nearly all of the IRIs will remain operative for decades (or forever). Future changes (if any) are likely to be only with properties:
- E.g., Labels (i.e., `rdfs:label`) 
- E.g., Synonyms (i.e., `skos:altLabel` and `skos:prefLabel`) - such as alternative names, or translations to other languages
- E.g., Definitions (e.g., `skos:definition`) 
- E.g., Sources (e.g., `rdfs:isDefinedBy`)
- E.g., Edges/relationships (e.g., `rdfs:seeAlso`, `sali:governedBy`)
- E.g., Multiple Parentage (e.g., additional `rdfs:subClassOf` parents)

The identifiers/IRIs themselves will remain static and stable.

## BRANCHES
Below is the branching strategy:
- `main` is  the stable branch
- `develop` is the draft, in-development branch

Eventually, `main` will have a formal Release (e.g., `LMSS 3.0` or `LMSS 4.0`). Until the Release, `main` remains unfinalized, but the IRIs will remain relatively stable.
