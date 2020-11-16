# Power BI Field Finder

Use the Power BI Field Finder to understand where in your report your columns and measures are being used.  Use this tool together with DAX Studio and the Power BI Helper to get a complete picture of your model and report.  Keep in mind this tool only shows you where fields are used in visuals and filters, not in relationships or measures.  Be careful before deleting columns and measures, especially if your model is being used in the service by other reports!

Disclaimer:  This is version 1.  Please let me know if you run into any errors with it.

# Instructions
Download the Power BI Field Finder.pbit template file.  

1.  Open the Power BI Field Finder.pbit file and you will be prompted to enter the path for the pbix file you'd like to analyze.  For example, if you your pbix file is saved in your C drive and is named "My Report", then the value for this parameter should be "C:\My Report.pbix".

2.  Click the Load button, and find your fields on the following pages!

3.  When you make changes to your pbix file, save it and refresh the Power BI Field Finder.  If you'd like to analyze a different report, update the parameter to the file path and filename of another pbix file.

# Sample File
The pbix used in the sample pbix file is based on the Power BI Desktop August 2019 update, which can be found here: https://github.com/microsoft/powerbi-desktop-samples/tree/master/Monthly%20Desktop%20Blog%20Samples/2019

# Known Issues
- If your table or field names contain parentheses or periods, the output table and field names will be wrong.  Fix currently in progress.

# Latest Changes
2020/11/16 - Replaced the old HTML viewer with the new one by Daniel Marsh-Patrick (https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA200001930). Incorporated Ried Haven's suggestion of a tooltip on the page thumbnails. Included the PowerBI.tips page backgrounds.

1.1 - No longer necessary to create a zip file, thanks to code contributions from Marco Russo (https://twitter.com/marcorus/status/1167486794990084096).

1.0 - First version

