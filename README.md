# securityReportGenerationAutomation
This project contains Jasper Report files confirming to a specific CSV input as the datasource containing security findings and autoimatically generates, executive summary report and a report of detailed findings.

To setup do the following - these steps have been made easy for individuals unfamiliar with Eclipse and Jasper Reports,

1. Download Jasper (link for windows) - http://iweb.dl.sourceforge.net/project/jasperstudio/JaspersoftStudio-6.1.1/TIBCOJaspersoftStudio-6.1.1.final-windows-x86_64.zip

2. Open the application and choose a location for workspace (you may leave it default).

3. Create a Jasper Reports Project (by clicking File --> New --> Other.

3. Move the jrxml files in the project forlder directly - you may copy from Windows Explorer and paste it there.

4. Create a datasource - in the repository explorer right click the data adapter and select type CSV - you will need to use the bug tracker saved as a CSV file when asked while setting up the datasource. Be sure to name the datasource - "Bug Tracker CSV Data Source".

5. Click Project build all.

6. Double click on the jrxml files and click on the poreview tab at the bottom - you should be able to see the report.

7. Click on the dropdown where Java is mentioned and select PDF or PPTX to see an exported version of the report.


Note the current bug tracker headings are,

TICKET CODE:
Related Tickets
FOUND BY:
ON DATE:
USING OS:
USING BROWSER:
USING TOOL:
BUG TYPE:
CATEGORY:
BUG TITLE:
BUG DESCRIPTION:
STEPS TO REPRODUCE:
RECOMMENDATION:
Environment
LOCATION/URL:
CVSS v2 RATING:
CVSSv2 Vector
LINK TO SCREENSHOT-1:
LINK TO SCREENSHOT-2:
LINK TO SCREENSHOT-3:
LINK TO LOG OR REPORT FILE-1:
LINK TO LOG OR REPORT FILE-2:
LINK TO MISC FILE:
NOTES:
References
MF_Additional_Reference
MF_IMG_PATH_1
MF_IMG_PATH_2
MF_IMG_PATH_3
MF_NORMALIZED_CVSSv2_RATING

