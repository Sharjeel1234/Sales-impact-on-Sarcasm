There are four folders.
refined-final: Folder contain all the relavent attribute for further sentimental analysis and its correlations.

scrapped-raw : contain files processed by default by ZONASINHUNTER 2. it contain 35 attribute list.
These csv files further refined in SQLLITE.

Refined-final: contain files processed in SQLLITE and refined by removing irrelavent attributes to
18 attributes.

scrappedtool-files: it contain project file for ZONASINHUNTER 2.

sqllitedb: it contain sqllite database file. which contain 4 tables.

actual1star table
actual2star table
actual3star table
actual4star table

https://deepmoji.mit.edu/

Go to site and take all reviews from 4 star , 3 star and check confidance score more than medium or equal because
these are sarcastic reviews. the validated reviews pass to keras model for prediction with other impact of sales. the sarcastic has 
worse impact which is initial finding of the project.

