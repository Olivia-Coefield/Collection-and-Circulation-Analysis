# Collection-and-Circulation-Analysis
# Readme
This dataset was created for a course at the University of Washington iSchool during the Winter quater of 2022. This dataset provides users with a breakdown of the usage pattern of books in academic libraries and is limited to the use of books and manuscripts. The intended audience is municipal policymakers. The dataset was created in 2011 and contains data from 2007-2008.

The dataset is in two formats, .csv and .xlxs. There is one table with no duplicate variables, though not all fields have been filled. 
# Table of Contents
* [Naming](https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis/blob/main/README.md#naming)
* [Data Dictionary](https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis/edit/main/README.md#data-dictionary)
* [Metadata](https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis/edit/main/README.md#metadata)
* [Security](https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis/edit/main/README.md#security)
* [Contact](https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis/edit/main/README.md#contact)

# Naming
Naming for files is as follows: 

*year_ShortDescription*

Where year is the year data was reported and ShortDescription is a brief description of the data being viewed. 

This naming convention was chosen as it immediately provides information on the type of data being viewed. Should this data be further explored past the years previously researched this provides information on how these files relate to other files, and allows for organization of data by years researched. 
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
|   Annual Circulation   |   Numeric           |   Any number                                        |   The number of times the item circulated in the year observed.                                                                                           |
# Metadata
|   Attribute           |                                                                                                                                                                                                                                                                            |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|   Metadata Type       |   Project Open Data                                                                                                                                                                                                                                                        |
|   accessLevel         |   Public                                                                                                                                                                                                                                                                   |
|   accrualPeriodicity  |   R/P1Y                                                                                                                                                                                                                                                                    |
|   fn                  |   Olivia Coefield                                                                                                                                                                                                                                                          |
|   hasEmail            |   mailto:oc22@uw.edu                                                                                                                                                                                                                                                       |
|   describedBy         |   https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis.git                                                                                                                                                                                               |
|   description         |   This dataset provides users with a breakdown of the usage pattern of books in academic libraries and is limited to the use of books and manuscripts. The intended audience is municipal policymakers. The dataset was created in 2011 and contains data from 2007-2008.  |
|   format              |   CSV                                                                                                                                                                                                                                                                      |
|   mediaType           |   CSV                                                                                                                                                                                                                                                                      |
|   issued              |   2022-03-06                                                                                                                                                                                                                                                               |
|   keyword             |   collection, circulation, usage pattern, academic libraries                                                                                                                                                                                                               |
|   landingPage         |   https://github.com/Olivia-Coefield/Collection-and-Circulation-Analysis                                                                                                                                                                                                   |
|   language            |   en-us                                                                                                                                                                                                                                                                    |
|   modified            |   2020-3-6                                                                                                                                                                                                                                                                 |
|   publisher           |   Olivia Coefield                                                                                                                                                                                                                                                          |
|   references          |   https://www.oclc.org/research/areas/systemwide-library/ohiolink/circulation.html                                                                                                                                                                                         |
|   license             |   http://www.oclc.org/research/activities/ohiolink/odcby.htm.                                                                                                                                                                                                              |
|   Rights              |   This data is freely available to the public.                                                                                                                                                                                                                             |
|   temporal            |   2022/P1Y                                                                                                                                                                                                                                                                 |
|   theme               |   collections and circulation                                                                                                                                                                                                                                              |
|   title               |   Collection and Circulation Analysis                                                                                                                                                                                                                                      |
# Security
This data is freely available to the public.
# Contact
Olivia Coefield, oc22@uw.edu
