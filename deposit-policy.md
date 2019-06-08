# Deposit Policy

Data regarding global location, food production, resources, and digital objects that further describe community gardens qualify for deposit into the Digging In Repository. Data describing current gardens may not be submitted without indicating if updates are due to a change in garden management or an update in garden data. New gardens will be added, and relationships to existing gardens will be documented through versioning.

All deposited data will require a contact for administrative use only, as well as a citation of their source of information. Research data will be accepted if it can provide the minimum viable package. Researchers using Digging In data are encouraged to use the DiggingInID number in their research to enhance relationships between gardens.

## Minimum Viable Package

Datasets in the Digging In repository are required to have the following elements:

* At least one instance in the dataset.
* Garden data must be submitted as a .csv. All datasets must have the variable labels in the first row. Data should be tidy with one variable per column and one observation per row.
* APIs may be used if they provide the minimum viable package
  * “If the data is available via an API, the API should be documented.” \(W3C Working Group, 2015\)
* Updated data will have versioning to indicate changes to the original object.
* All datasets must contain the garden’s name \(text\), latitude \(number\), longitude \(number\), if it is food producing \(boolean\), state name, county name, and census tract.
* All datasets must have unique identifiers assigned to gardens. These identifiers will be mapped onto Digging In Unique IDs
* All data stored on Digging In must follow licensing policies as explained in the section on [Licensing.](https://lis598j-buechlerhammerquist.gitbook.io/digging-in-community-garden-data/licensing)

## Accepted Formats

Non-proprietary formats are required for garden data. In addition to the .csv, shape files may also be submitted. Shape files are a package of at least three files that provide geo-spatial information about gardens. Required shape files are: a .shp file, .dbf file, and .shx index file. Shape files are not required for submission but are highly encouraged as they create a digital representation of the space and orientation of your garden\(s\). Shape files can be created with [QGIS open-source software](https://www.qgis.org/en/site/). Digging In will not accept unstructured data, including: .pdf, .jpg, .tiff, and .png. File size will vary but should generally be low-medium.

## Preservation Guarantees

Digging In will do everything possible to ensure that data maintains its integrity. Submitting data in highly recommended formats guarantees our ability to preserve your data. Data submitted in less or not recommended formats may be returned for revisions, ****subject to [transformation](https://lis598j-buechlerhammerquist.gitbook.io/digging-in-community-garden-data/transformation), or unable to be preserved. For more information on format recommendations please see the table below:

| Content Type | Highly Recommended Formats | Less Recommended Formats | Not Recommended Formats |
| :--- | :--- | :--- | :--- |
| datasets | .csv, .tsv | .csv, .tsv | .xlsx |
| shape files | .shp, .shx, .dbv | .prj, .sbn, .sbx | - |
| text files | .xml, .txt | - | .docx |

Comma-separated values are the most common file submitted to Digging In. he organization of your data within each file will also affect Digging In’s ability to preserve and re-use your information. Following the standard set forth by Hadley Wickham in “Tidy Data,” CSV data should conform to the following:

1. Each variable forms a column.
2. Each observation forms a row.
3. Each type of observational unit forms a table

