# Collection-and-Circulation-Analysis
# Readme
This dataset was created for a course at the University of Washington iSchool during the Winter quater of 2022. It is a breakdown of collection and circulation analysis in order to understand usage patterns 
# Table of Contents
* Naming
* Data Dictionary
* Metadata
* Security
* Contact

# Naming
# Data Dictionary
|   Variable             |   Measurement Unit  |   Allowed Values                                    |   Description                                                                                                                                             |
|------------------------|---------------------|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|   Item No.             |   Numeric           |   Numbers within OhioLINK database                  |   An identifier that is unique for each item within a source file.  The combination of source id and item number is unique within OhioLINK.               |
|   OCLC No.             |   Numeric           |   Numbers within the WorldCat bibliographic record  |   Number for the corresponding WorldCat bibliographic record.                                                                                             |
|   Work No.             |   Numeric           |   Numbers within the OCLC Workset algorithm         |   The Work number as identified by the OCLC Workset algorithm.                                                                                            |
|   Source               |   Text              |   Institution names                                 |   Name of the institution supplying the data.                                                                                                             |
|   Campus               |   Text              |   College campus names                              |   The name of the campus generating the circulation.                                                                                                      |
|   Administrative Unit  |   Text              |   Administrative unit names                         |   The name of the administrative unit for the libraries generating the circulation.  This will be null if the campus does not have administrative units.  |
|   Subunit              |   Text              |   Subunit names within administrative unit          |   The name of the subunit within the administrative unit generating the circulation.  This will be null if the administrative does not have subunits.     |
|   Accession Date       |   Date              |   Any date                                          |   The date the book was acquired or entered into the system whichever is later.                                                                           |
|   Date of Last Use     |   Date              |   Any date                                          |   The date the item last circulated.                                                                                                                      |
|   Circulation Status   |   Numeric           |   Number between 0 and 1                            |   A code indicating whether the item is circulating or non-circulating.                                                                                   |
|   Total Circulation    |   Numeric           |   Any number                                        |   The total number of times the item has circulated since being entered into the system.                                                                  |
|   Annual Circulation   |   Numeric           |   Any number                                        |   The number of times the item circulated in the year observed.                                                                                           |# Metadata
# Security
# Contact
