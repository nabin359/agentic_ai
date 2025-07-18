 

New link as of 5/22/2020. https://workforce.usps.gov/

Login using your credentials

Go to Dashboards tab

Go to F2|City Delivery option

Go to Filter option near upper left

Click Finance radio button under Ranking Level and wait for it to load

Click the Export button (down arrow) at the top of the grid, far right

It will take longer than expected to run and give you an option to download, (20-30 sec or more).

 

Then choose Export, Save As, then open in Excel. Don’t worry about leading zeroes being missing, the stored proc handles them.

 

Open the non_ams_rtes_template.csv file found in the \\eagnmnwbp1665\data\FieldStaffing   folder

 

Copy all the values from the following columns in the workforce dashboard export file into the following columns in the template file (6 columns in total):

 

Finance Number,Non-AMS Collection,Non-AMS Combo,Non-AMS Parcel,Non-AMS Router,Non-AMS VOMAs

 

Save the updated template file as non_ams_rtes.csv in the FieldStaffing folder

 

Run Job NON_AMS_ROUTES in CSV 1241 using GUI:



 

Check that file has been processed and place in FieldStaffing\Backup folder

 

Done.

 
