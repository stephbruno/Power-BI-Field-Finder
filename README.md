# Power BI Field Finder

Use the Power BI Field Finder to understand where in your report your columns and measures are being used.  Use this tool together with DAX Studio and the Power BI Helper to get a complete picture of your model and report.  Keep in mind this tool only shows you where fields are used in visuals and filters, not in relationships or measures.

# Instructions
Download a copy of the Power BI Field Finder.pbix to you computer and open it.  The instructions below are also on the first page of the report.

1.  Save a copy of your pbix file somewhere locally and rename the file extension to zip.  For example, change "Copy of My Report.pbix" to "Copy of My Report.zip".  This will convert your copied pbix file to a zip file.

2.  Extract your new zip file to a folder.

3.  Take a look at the files in there!  For info on what they're all for, see this great post by Gilbert Quevauvilliers:  https://www.fourmoo.com/2017/05/02/what-makes-up-a-power-bi-desktop-pbix-file/ and also this one by Reza Rad:  https://radacad.com/exposing-m-code-and-query-metadata-of-power-bi-pbix-file 

4.  Change the parameter in this pbix file for "Extracted zip file top level folder" to the path including the name of your extracted folder.  For example, if you saved your extracted folder to "C:\Copy of My Report", then that should be the value for the parameter.

5.  Click the Refresh button, and find your fields on the following pages!

6.  When you make changes to your pbix file, re-do steps 1 to 5 to reflect your changes.

# Sample File
The pbix used in the sample file is based on the Power BI Desktop August update, which can be found here: https://github.com/microsoft/powerbi-desktop-samples/tree/master/2019

