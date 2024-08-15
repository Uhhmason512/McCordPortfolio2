ExcelPopulate and UpdateYTD

The ExcelPopulate script was something created for the Boeing Hack-a-Thon. The premise is that whenever a new excel of raw data is pulled from a web application related to the Boeing databases, this data will be automatically populated within a prioritization excel that ranks and assigns audits.

Features include assigning audits to faciliators based on geographic location, preserving macros, etc. 

Streamlit was used until the script was packaged into an executable to deliver to stakeholders. Streamlit generally needs to be run through a command window, so even though work arounds were found, run time was slow and the modules didn't package well. PyQT was then administered, an uglier UI but worked for our purposes.

The base functionality of populating data was then brought over to UpdateYTD. This script is more universal and simple, and is recomended for anyone wanting to populate data from one excel to another.
