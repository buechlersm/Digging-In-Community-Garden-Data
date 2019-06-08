# Transformation

## **Format Conversion**

When possible, and when it can prohibit the loss of data, datasets will be converted to the following formats:

| File Type | Format |
| :--- | :--- |
| Datasets | .csv |
| Shape files | .shp |
| Text files | .txt |

If data loss is a concern, the level of affect to reusability will be assessed. In all instances where is determined reusable, data will be stored in its original and converted formats. If reusability cannot be determined, data will be stored and made available in its original format.

If reusability is impaired by format conversion and is:

1. collected by the repository team, data will be stored using original and converted formats. -OR-
2. submitted by a data collector, data will be stored using original and converted formats

## **Data Cleaning**

In order to ensure reusability, all data will be subject to cleaning prior to storage in repository. Choices on data cleaning are derived from Karl W. Broman and Kara H. Woo’s article, “Data Organization in Spreadsheets,” and Hadley Wickham’s, “Tidy Data.”

The following practices are standardized for Digging In:

* Removal:
  * Special characters
  * Blank columns & rows
  * Punctuation & symbols from numerical attributes
  * Non-tabular information within tabular data \(e.g. footnotes, keys and legends\)
* Formatting:
  * Numbers shortened to the hundredth decimal point when appropriate
    * Location based numbers excluded from decimal point rule
  * Location:
    * Geospatial coordinates will be divided into separate “Latitude” and “Longitude” columns
    * Addresses will be separated into the following variable columns:
      * Street Address
      * City
      * State
      * Zip Code
  * Dates will conform to ISO 8601 format of YYYY-MM-DD
* Null values
  * In instances where an attribute is null for a specific variable, it will be replaced with “N/A” to signify intentionality in lack of data

## **File Naming Conventions**

File names will adhere to the following conventions:

* Will not:
  * Include special characters
  * Spacing
  * Exceed 60 characters
* Will:
  * Use Camel Casing \(e.g. CommunityGardenData for Community Garden Data\)
  * Use underscores to separate filename elements \(e.g. CommunityGarden\_ReadMe\)

File names for datasets will contain the following information, where applicable, and in the following order:

1. Subject/dataset name \(mandatory\)
2. DiggingIn ID \(mandatory\)
3. File context
   1. Master level documents will always be tabular or shape file data and will not contain this element
   2. All subsequent documentation will follow with a descriptor
      1. Multiple datasets, or datasets derived from a multi-sheet .xsl file, will contain the following quantifier: Sheet\#
      2. ReadMe - for all text-based supplemental documentation
4. Versioning \(see section below\)

Examples;

CommunityGarden\_DI003

CommunityGarden\_DI003\_ReadMe  


File names for individual gardens, as submitted by participant and ingested by Digging In will contain the following elements in the order outlined, as applicable:

1. Garden name \(mandatory\)
2. Garden Location \(mandatory
   1. City
   2. State Abbreviation
      1. \(e.g. SeattleWA\)
3. Digging In ID
4. Versioning \(see section below\)

## **Versioning**

The first submission of a garden will be \[Garden\]\_1.0. Updates to a gardens data will be indicated by an increase in the integer to the right of the decimal point. Changes that fundamentally alter the garden’s aboutness, such as changes in ownership or the garden’s structure will be reflected in an increase in the integer to the left of the decimal. If a garden’s name is changed the versioning should restart from 1.0 but relationships to the past gardens in the space must be documented referring to the Digging In ID Number.  


