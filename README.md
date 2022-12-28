# MNA Attendance

Downloads and extracts member attendance data from the Pakistan National Assembly [website](https://na.gov.pk). 

Attdendance data is available for download in PDF format on a single [web page](https://na.gov.pk/en/attendance2.php). 

PDF files are downloaded and saved after parsing the web page and extracting relevant hyperlinks. 

Downloaded files are processed via [tabula](https://tabula-py.readthedocs.io/en/latest/index.html) and table is extracted as CSV files. Some minor data is discarded, for now. 

CSV files are then combined into one single dataset using [Pandas](https://pandas.pydata.org/). 

__Note__: Data needs manual cleaning, as names of members do not match [officially published lists](https://na.gov.pk/en/all_members.php). Some members have passed away, some have resigned, and data on some seats has not been updated. Member data was imported into Microsoft Excel directly via the web 

Final cleaned data is available [here](https://docs.google.com/spreadsheets/d/1hh6BbP7Z5MKDC9S2Z5SAcyTRPkAqC4HTF_wqsWd6Wes/edit?usp=sharing)

