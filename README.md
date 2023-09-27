# Power BI Field Finder

Use the Power BI Field Finder to understand where in your reports your columns and measures are being used and find the ones that aren't being used at all.  Be careful before deleting columns and measures, especially if your model is being used in the service by other reports! Update: to analyze multiple reports and the associated dataset, use the new Field Finder (with data model) files!

Disclaimer:  This is a side project and is not perfect.  Please let me know if you run into any errors with it.

# Instructions
Download the Power BI Field Finder.pbit template file.  

1.  Open the Power BI Field Finder.pbit file and you will be prompted to enter parameters for the folder where your reports are, the database server, and the database name.

2.  Click the Load button, and find your fields on the following pages!

3.  When you make changes to your reports, save them and refresh the Power BI Field Finder.  If you'd like to analyze different reports or datasets, update the parameters.

Further information can be found in this blog post: https://data-witches.com/2020/11/17/power-bi-field-finder/

# Sample File
The pbix used in the original sample pbix file is based on the Power BI Desktop August 2019 update, which can be found here: https://github.com/microsoft/powerbi-desktop-samples/tree/master/Monthly%20Desktop%20Blog%20Samples/2019.
For the new version with multiple reports and a shared dataset, see the Adventure Works and Sales Report files.

# Known Issues
- 

# Latest Changes
2023/09/27 - 
- Added support for connecting to a data model to compare all data model fields with the fields used in visuals and filters.
- Changed from analyzing a single file to allowing for all files under a folder.
- Fixed issues with column names with special characters.

2020/11/16 - Replaced the old HTML viewer with the new one by Daniel Marsh-Patrick (https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA200001930). Incorporated Ried Haven's suggestion of a tooltip on the page thumbnails. Included the PowerBI.tips page backgrounds.

1.1 - No longer necessary to create a zip file, thanks to code contributions from Marco Russo (https://twitter.com/marcorus/status/1167486794990084096).

1.0 - First version

