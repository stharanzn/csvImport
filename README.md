### Replicate the project
* Create a GCP (Google Cloud Platform) project from the google console and enable the following API's
    - Apps Script API
    - Google Sheets API	    
    - Google Workspace Marketplace SDK
* After enabling them setup the OAuth consent screen to Type user type External, skip the scopes and add the test user emails according (make sure to add ur email in the test users).

* After that open a new spreadsheet and go to extensions and select app scripts

* a new tab with the app scripts editor will open up.

* create a new html file named csvImport.html and copy paste the codes from the AppScript folder respectively. 

* for the first time you will have to run the project and the execution should be successful (In the OAuth consent screen click on continue and allow).

* after that go the the spreadsheet and now there should be a new menuitem named NowStackit with the import options.
