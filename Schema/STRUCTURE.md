# Schema Directory Structure

This document outlines the complete hierarchical structure of the Schema.org vocabulary implementation.

## Overview

The Schema/ directory contains a comprehensive mapping of all Schema.org entities organized in a hierarchical structure:

- **909 directories** containing entity definitions
- **912 entity markdown files** (.md files)
- **Complete parent-child relationships** as defined in Schema.org

## Directory Structure

```
Schema/
|- Schema.md (Main schema documentation)
|- README.md
|- STRUCTURE.md (this file)
|- DataType/
|  |- Boolean/
|  |  |- False/
|  |  |  |  |- False.md
|  |  |- True/
|  |  |  |  |- True.md
|  |  |  |- Boolean.md
|  |- Date/
|  |  |  |- Date.md
|  |- DateTime/
|  |  |  |- DateTime.md
|  |- Number/
|  |  |- Float/
|  |  |  |  |- Float.md
|  |  |- Integer/
|  |  |  |  |- Integer.md
|  |  |  |- Number.md
|  |- Text/
|  |  |- CssSelectorType/
|  |  |  |  |- CssSelectorType.md
|  |  |- PronounceableText/
|  |  |  |  |- PronounceableText.md
|  |  |- URL/
|  |  |  |  |- URL.md
|  |  |- XPathType/
|  |  |  |  |- XPathType.md
|  |  |  |- Text.md
|  |- Time/
|  |  |  |- Time.md
|  |  |- DataType.md
|- Thing/
|  |- Action/
|  |  |- AchieveAction/
|  |  |  |- LoseAction/
|  |  |  |  |  |- LoseAction.md
|  |  |  |- TieAction/
|  |  |  |  |  |- TieAction.md
|  |  |  |- WinAction/
|  |  |  |  |  |- WinAction.md
|  |  |  |  |- AchieveAction.md
|  |  |- AssessAction/
|  |  |  |- ChooseAction/
|  |  |  |  |- VoteAction/
|  |  |  |  |  |- ChooseAction.md
|  |  |  |- IgnoreAction/
|  |  |  |  |  |- IgnoreAction.md
|  |  |  |- ReactAction/
|  |  |  |  |- AgreeAction/
|  |  |  |  |- DisagreeAction/
|  |  |  |  |- DislikeAction/
...
(showing first 50 entries - complete structure contains 1558 entries)
```

## Organization Principles

### Main Categories

The top-level entities under Thing/ include:

1. **Action/** - Actions performed by direct agents and indirect participants
2. **BioChemEntity/** - Biological and chemical entities  
3. **CreativeWork/** - Creative works including articles, books, movies, photographs, software programs
4. **Event/** - Events including concerts, meetings, festivals, sports events
5. **Intangible/** - Abstract concepts, ratings, roles, languages
6. **MedicalEntity/** - Medical and health-related entities
7. **Organization/** - Organizations including businesses, educational institutions, NGOs
8. **Person/** - People, both real and fictional
9. **Place/** - Geographic locations, physical spaces, addresses
10. **Product/** - Products and services offered by organizations
11. **Taxon/** - Taxonomic groupings of organisms

### Data Types

The DataType/ directory contains:

- **Boolean/** - True/False values
- **Date/** - Date values
- **DateTime/** - Date and time values  
- **Number/** - Numeric values (Float, Integer)
- **Text/** - Text values including URLs and special text types
- **Time/** - Time values

### Hierarchy Rules

1. Each entity has its own directory containing:
   - `EntityName.md` - The main entity definition file
   - Subdirectories for any child entities

2. Each `.md` file contains:
   - Entity description
   - Schema.org details (Type, URI)
   - Parent class references
   - Child class listings (when applicable)

3. Parent-child relationships follow the official Schema.org hierarchy

## Generation

This structure was automatically generated from the official Schema.org hierarchy to ensure:
- Complete coverage of all Schema.org entities
- Proper parent-child relationships
- Consistent directory and file naming
- Maintainable structure for future updates

## Statistics

- Total directories: 909
- Total entity files: 912
- Hierarchical depth: Up to 6 levels deep
- Coverage: Complete Schema.org vocabulary as of the generation date

## Usage

Navigate the hierarchy by following the directory structure. Each entity's `.md` file contains links to:
- Its parent entity (going up the hierarchy)
- Its child entities (going down the hierarchy)

This enables easy exploration of the complete Schema.org vocabulary in a structured, navigable format.
