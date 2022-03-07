This is a guide to using CalAnswers to generate the raw data for the repository.

# Initial steps
 
1. Gain access to [CalAnswers](https://calanswers.berkeley.edu/getting-access-cal-answers).
2. Log-in to CalAnswers. Under navigate to Student Data Dashboards > Student Applicants and then the relevant type (undergraduate or graduate)

# Getting a master link for A/A/SIR
Once you have followed the initial steps: 
1. Navigate to the applicant counts page. 
2. In the filters bar, apply the broadest criteria possible (i.e. selecting every year and selecting nothing for derived residency, semester, and applicant type). Doing this ensures that we miss none of the data. 
3. Now, repeatedly expand every categorization in each of the three tables until you can no longer expand any categorization. (Tip: searching "collapsed" in the developer dashboard of your browser should help you find the categories that are yet to be expanded.)
4. After expanding every category and making sure that every row of every table is visible, go to the settings gear and click "Create Bookmark Link." Save this link; this is the master link. 

The master link for undergraduate applicants as of March 6, 2022, is https://calanswers-bi.berkeley.edu:9503/analytics/saw.dll?Dashboard&PortalPath=%2Fshared%2FStudent%20Applicants%2F_portal%2FUndergraduate%20Applicants&Page=UG%20Applicant%20Counts&PageIdentifier=o9ttqb52kstr0gm3&BookmarkState=j7vgjuhplv6bre5qu8sbl1jobq&options=-.

# Getting data from a master link
Once you have a master link, you can get the data in the following manner: 
1. Open the master link (this is important; do not start from a different dashboard state or you may not capture some data).
2. Use the filters to get the relevant data.
3. Make sure that every table is wholly visible (i.e. ensure that more than the first 25 rows are visible). If you do not do this, only the first 25 rows of the data will be exported. 
4. Under each table on the page, click "export" and then a useful data type. I recommend either excel or XML. CSV does not properly preserve the data. 
5. Wait for the export to finish, then save the file with a readable file name. 
6. Now, generate a link for this dataset by going to the settings gear and clicking "Create Bookmark Link." 
