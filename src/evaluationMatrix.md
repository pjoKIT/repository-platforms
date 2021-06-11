## Evaluation Matrix

Status: 08.06.2021

| Function              | [AIMS](aims/atAGlance.md) | [Ckan](ckan/atAGlance.md) | [Cordra](cordra/atAGlance.md) | [Coscine](coscine/atAGlance.md) | [DSpace](dspace/atAGlance.md) | [Fedora](fedora/atAGlance.md) | [Gerdi](gerdi/atAGlance.md) |[Invenio](invenio/atAGlance.md) | [Metastore](metastore/atAGlance.md) | [OSF](openScienceFramework/atAGlance.md) | [Zenodo](zenodo/atAGlance.md) |
| ---------------------:| :-----------------------: | :-----------------------: | :---------------------------: | :-----------------------------: | :---------------------------: | :---------------------------: | :-------------------------: | :----------------------------: | :---------------------------------: | :--------------------------------------: | :---------------------------: |
| Register Schema       |                           | -                         | (+)[^1]                       |                                 |  -                            | -                             | -                           | -                              | +                                   | -                                        | -                             | 
| Update Schema         |                           | -                         | (+)[^2]                       |                                 |  -                            | -                             | -                           | -                              | +                                   | -                                        | -                             | 
| Validate Schema       |                           | -                         |  -                            |                                 |  -                            | -                             | -                           | -                              | +                                   | -                                        | -                             | 
| Ingest Metadata       |                           | +                         |  +                            |                                 |  +                            | +                             | +                           | +                              | +                                   | +                                        | +                             | 
| Update Metadata       |                           | +                         |  +                            |                                 |  +                            | +                             | +                           | +                              | +                                   | +                                        | +                             | 
| Validate Metadata     |                           | -                         |  +                            |                                 |  -                            | -                             | +                           | -                              | +                                   | -                                        | -                             | 
| Search by ...         |                           |                           |                               |                                 |                               |                               |                             |                                |                                     |                                          |                               | 
| ... Administrative MD |                           | +                         |  +                            |                                 |  +                            | +                             | +                           | +                              | +                                   | +                                        | +                             | 
| ... Content           |                           | -                         |  +                            |                                 |  -                            | +                             | +                           | -                              | (+)                                 | -                                        | -                             | 
| Persistent Identifier |                           | +                         |  +                            |                                 |  +                            | +                             | +                           | +                              |  +                                  | +                                        | +                             | 

For more detailed information please use the links in the table header.

### Description 
- **Register Schema:**
  - Support for arbitrary schemas of a specific format (e.g. JSON Schema, XSD)
- **Update Schema:**
  - Possibility to 
    - work on different versions of a schema 
    - adapt schemas over time
- **Validate Schema:**
  - Check schema for correct syntax
- **Ingest Metadata:**
  - Store metadata (document) in repository
    - Ideally with previous validation 
- **Update Metadata:** 
  - Possibility to update already ingested metadata (documents).
- **Validate Metadata:**
  - Possibility to validate documents on the basis of registered schemas.
- **Search by Administrative MD:**
  - Search documents by their metadata (e.g. ingest date, ingester, ...)
- **Search by Content:**
  - Search documents by their content
- **Persistent Identifier:**
  - Support for Persistent Identifiers (e.g. DOI, Handle)

---
**Footnotes**

[^1]: Support for arbitrary (JSON Schema) via configuration only (-> restricted to administrators)

[^2]: Manually by administrators
