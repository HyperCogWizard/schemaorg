# Schema.org Documentation

This directory contains structured documentation for Schema.org types organized by their hierarchical relationships.

## Structure

The documentation is organized according to the core Schema.org type hierarchy:

### Thing Types
The `Thing/` directory contains documentation for the core Schema.org types that inherit from the base `Thing` class:

- **Action**: Actions performed by agents upon objects
- **BioChemEntity**: Biological and chemical entities  
- **CreativeWork**: Creative works like articles, books, movies, etc.
- **Event**: Events such as concerts, meetings, festivals
- **Intangible**: Abstract concepts like ratings, roles, languages
- **MedicalEntity**: Medical and health-related entities
- **Organization**: Organizations including businesses, schools, NGOs
- **Person**: People, both real and fictional
- **Place**: Geographic locations and spaces
- **Product**: Products and services offered
- **Taxon**: Taxonomic groupings of organisms

### DataType Types  
The `DataType/` directory contains documentation for Schema.org basic data types:

- **Boolean**: True/false values
- **Date**: Date values
- **DateTime**: Date and time values  
- **Number**: Numeric values
- **Text**: Text strings
- **Time**: Time values

## Usage

Each type has its own directory containing:
- A markdown file with the type's definition, description, and relationships
- Links to parent and child classes in the hierarchy

## Schema.org Reference

For the complete Schema.org specification, visit [schema.org](https://schema.org/).

This documentation is generated from the official Schema.org RDF vocabulary definitions.