# Distressed Housing Tracts, 2022 on

This dataset extracts the columns for distressed tracts from the FFIEC compilation of census data, for use in their FFIEC Census Windows Application. It includes only 25 columns, the first 17 columns of the file, which have geographic identifiers, median income, and three population totals. The reamaining 8 columns hold flags to indicate if a tract is distressed. 

* 1205	Identifies Income Level Indicator 
* 1206	Meets current year's poverty CRA distressed criterion? 
* 1207	Meets current year's unemployment CRA distressed criterion? 
* 1208	Meets current year's population CRA distressed criterion?  
* 1209	Meets current year's remote rural (low density) CRA underserved criterion? 
* 1210	Meets at least one of the previous year's CRA distressed criteria?  
* 1211	Meets previous year's CRA underserved criterion? 
* 1212	Meets at least one of current or previous year's CRA distressed/underserved tract criteria? 


## Caveats

The 2017 file, as distributed by FFIEC, is broken: it includes a ZIP file with in the ZIP file, which Metapack cannot read. This file has been manually extracted and stored in the source package. 