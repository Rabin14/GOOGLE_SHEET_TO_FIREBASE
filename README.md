Sheets to Firebase
Create a new Google Sheet
Change the file name from 'Untitled Spreadsheet' to 'Firebase' (non-essential)
Change the sheet name from 'Sheet 1' to 'Users' (non-essential)
Open the 'Tools' menu
Open 'Script Editor'
Change the script name from 'Untitled' to 'Firebase' (non-essential)
Open the 'View' menu
Click 'Show manifest file'
Open appscript.json and add the following oAuth scopes

#############################################################################

Open Code.gs
Delete all the existing code in Code.gs and replace it with the code from appscript/update-firebase.js,
taking care not to include the imports/exports which are for testing purposes only.
Initialize
run the code
