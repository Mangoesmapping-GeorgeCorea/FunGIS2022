# From QGIS Desktop to the Web/Mobile and back - Spatial Olympics 2023

The repo covers the worshop on QGIS Web and Mobile at the 2022 conference and has been updated for the 2023 Spatial Olympics.

## SPATIAL OLYMPICS 2023
The focus here is only on the essentials required for Spatial Olympics.

Download QField:
Go to your phone's app store (like the Apple App Store or Google Play Store).
Search for "QField".
Find the app in the search results and tap on "Install" or "Download".

Create a QField Account:
Open the QField app on your phone.
Tap on "Sign Up" or "Create Account".
Fill in your details like your email, create a password, and follow the on-screen instructions.
Email your username or email address to data+fungis@mangoesmapping.com.au

Open the Project:
After your request has been approved, go back to the QField app.
Look for the "QField Cloud Projects" section and tap on it.
Click on "Community"
You should see the 'FungisSpatailOlympics2023' project listed (by FunGISFNQ). Tap on it.
The project will open, and you can start exploring or working on it!

See the Presentation below on how to use QField - the specifics for this excercise are...
*Presentation - https://docs.google.com/presentation/d/1CByOhTp2gIikvCrLhYvZxTFb_uyvbHkk/edit?usp=sharing&ouid=112298073149416757204&rtpof=true&sd=true

In QField (while on the activity)
- Click on the Epsilon on the left, Cloud Icon and Synchronise to get the new data.
- Add points to the 'QandA' layer (1 point for the right answer,1 point for a location point and 1 point for a photo of the group at the entrance of the building). Refer to the questions above for complete detail as in QField and QGIS this is truncated but the Question numbers are the same.
- Bonus points for tracking your route (10m interval) and shortest distance travelled between the most number of points (use the 'Tracklog' layer).
- The 'Locations' layer indicates where the building center point is.
- Export the table once done (45 mins from start of activity) as a GPKG and email to data+fungis@mangoesmapping.com.au
- Click the cloud icon and then 'Push'. Do not use 'Synchronise'. (Emailing data is just as a backup - please do this first.)
Refer presentation from 2022 for details on using QField - http://tiny.cc/QField_QuickGIS (Slide 26 onwards)

  
## ChatGPT Plus prompts to get this
- Initial collection of information and exploration of complex possibilies - https://chat.openai.com/share/05c8fd5e-730d-48ed-b75c-e140089b8d03
- Creating the inputs required for QGIS - https://chat.openai.com/share/d3882bf3-6f50-4db8-9ccd-628a1bdc8d11
- Creating a simple guide - https://chat.openai.com/share/ce37e8ae-d150-46ab-b6ae-f2fd07f26505
- Analysing the results - https://chat.openai.com/share/ad6bcf83-42c2-4a4a-a4d7-005a088532ee

## MINIMUM REQUIREMENTS
1. QGIS 3.26 or above from https://qgis.org/en/site/forusers/download.html
2. Install QField Sync plugin into QGIS Desktop - https://plugins.qgis.org/plugins/qfieldsync
3. QField on your device (Android,iOS,MacOS and Windows) from https://docs.qfield.org/get-started/
	- When you open it you should see QFieldCloud Projects
	- if not please install the dev version (android only) from https://play.google.com/store/apps/details?id=ch.opengis.qfield_dev 


## FOLDER STRUCTURE

*QField_Staging - Project and data for Web and Mobile sync

*Cheat_Files - Predesigned projects/data for skipping steps

*Presentation - https://docs.google.com/presentation/d/1CByOhTp2gIikvCrLhYvZxTFb_uyvbHkk/edit?usp=sharing&ouid=112298073149416757204&rtpof=true&sd=true
