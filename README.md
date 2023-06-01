# EGS-Star-Catalogue-exporter
This executable will export the logs necessary to enable the EGS Star Catalogue in Google Sheets

Place this file in an easy-to-locate directory. When you run it, it will prompt you for the Empyrion save that you would like to use. Navigate to your savegame directory and select 'global.db'. The program will create 3 .csv files: 
Star Log.csv
Playfield Log.csv
POI Log.csv

Then, go to your copy of the EGS Star Catalogue in Google Sheets and run the 'Import Logs' script. It will prompt you to select some files. Choose the 3 .csv files that were created, and then upload them.
That should be it! It's time to find your stuff.

**NOTE** I am not a programmer or in any way proficient at coding/scripting. This was created by asking ChatGPT to make things for me. The database queries were modified by me from another redditor, u/Bleyo.

Thank you to Bleyo for sqlite query help,
teakeycee for beta testing and making sure directions are easy to follow,
stanlahey for the trader data used in the Star Catalogue,
and the rest of the EGS community for support and being all around good eggs.
