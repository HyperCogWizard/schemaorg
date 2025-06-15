# Schema.org Vocabulary

Schema.org is a collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.

## Overview

Schema.org vocabulary consists of a set of 'types', each associated with a set of properties. The types are arranged in a hierarchy. The core vocabulary currently consists of 813 Types, 1,480 Properties, and 15 Datatypes.

## Core Types

### Thing
The most generic type in Schema.org. All other types inherit from Thing.

### Major Categories

1. **[Action](Thing/Action/Action.md)** - Actions performed by direct agents and indirect participants upon direct objects
2. **[CreativeWork](Thing/CreativeWork/CreativeWork.md)** - Creative works including articles, books, movies, photographs, software programs, etc.
3. **[Event](Thing/Event/Event.md)** - Events including concerts, meetings, festivals, sports events, etc.
4. **[Intangible](Thing/Intangible/Intangible.md)** - Abstract concepts, ratings, roles, languages, etc.
5. **[Organization](Thing/Organization/Organization.md)** - Organizations including businesses, educational institutions, NGOs, etc.
6. **[Person](Thing/Person/Person.md)** - People, both real and fictional
7. **[Place](Thing/Place/Place.md)** - Geographic locations, physical spaces, addresses
8. **[Product](Thing/Product/Product.md)** - Products and services offered by organizations

### Specialized Types

- **[BioChemEntity](Thing/BioChemEntity/BioChemEntity.md)** - Biological and chemical entities
- **[MedicalEntity](Thing/MedicalEntity/MedicalEntity.md)** - Medical and health-related entities  
- **[Taxon](Thing/Taxon/Taxon.md)** - Taxonomic groupings of organisms

## Data Types

Schema.org defines several basic data types for use with properties:

- **[Boolean](DataType/Boolean/Boolean.md)** - True/false values
- **[Date](DataType/Date/Date.md)** - Date values
- **[DateTime](DataType/DateTime/DateTime.md)** - Date and time values
- **[Number](DataType/Number/Number.md)** - Numeric values including integers and floats
- **[Text](DataType/Text/Text.md)** - Text strings
- **[Time](DataType/Time/Time.md)** - Time values

## Usage

Schema.org vocabulary can be used with many different encodings, including RDFa, Microdata and JSON-LD. The vocabulary is used by millions of sites for purposes including:

- Search engine optimization
- Content management
- Data integration
- Knowledge graphs
- Semantic applications

## Extensions

The core Schema.org vocabulary is complemented by several domain-specific extensions covering areas like healthcare, automobiles, bibliography, and more.

## More Information

- **Main site**: [schema.org](https://schema.org/)
- **Developer documentation**: [schema.org/docs](https://schema.org/docs/)  
- **GitHub repository**: [github.com/schemaorg/schemaorg](https://github.com/schemaorg/schemaorg)
- **Community group**: [W3C Schema.org Community Group](https://www.w3.org/community/schemaorg/)

This documentation was generated from the official Schema.org RDF vocabulary definitions.