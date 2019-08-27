# Power BI Field Finder

Use the Power BI Field Finder to understand where in your report your columns and measures are being used.  Use this tool together with DAX Studio and the Power BI Helper to get a complete picture of your model and report.  Keep in mind this tool only shows you where fields are used in visuals and filters, not in relationships or measures.

Disclaimer:  This is version 1.  Please let me know if you run into any errors with it.

# Instructions
Download the Power BI Field Finder.pbit template file.  

1.  Save a copy of your pbix file that you want to analyze somewhere locally and rename the file extension to zip.  For example, change "My Report - Copy.pbix" to "My Report.zip".  This will convert your copied pbix file to a zip file.

2.  Extract your new zip file to a folder and copy the location of this folder, including the folder name.  For example, if you saved your extracted folder to "C:\My Report", then that's the value you want.

3.  If you're curious, take a look at the files in there!  For info on what they're all for, see this great post by Gilbert Quevauvilliers:  https://www.fourmoo.com/2017/05/02/what-makes-up-a-power-bi-desktop-pbix-file/ and also this one by Reza Rad:  https://radacad.com/exposing-m-code-and-query-metadata-of-power-bi-pbix-file 

4.  Open the Power BI Field Finder.pbit file and you will be prompted to enter the path you copied in step 2.  

5.  Click the Load button, and find your fields on the following pages!

6.  When you make changes to your pbix file, re-do steps 1 to 3, and update the parameter in the report to reflect your changes.

# Sample File
The pbix used in the sample pbix file is based on the Power BI Desktop August 2019 update, which can be found here: https://github.com/microsoft/powerbi-desktop-samples/tree/master/2019

