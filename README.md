# sheets-editor

## Functionalities Implemented
- Users can add new Name-Surname pairs to their spreadsheet
- Users can enter names and get their corresponding surnames (might be more than one) in a list
- If there are no surnames found, the screen will display `Nothing Found` 

## How to Test
- Create a Google Cloud project by following these steps: https://developers.google.com/workspace/guides/create-project
- Enable Sheets API inside the project
- Get an API key and OAuth client ID by following these steps: https://developers.google.com/workspace/guides/create-credentials
- Go to the created project on https://console.cloud.google.com/ and open OAuth Consent Screen
- IMPORTANT: Add the email to be used for testing the app in this section.
  - ![image](https://user-images.githubusercontent.com/72245964/163204056-1b26bf24-b178-44b7-9e44-6846c8126253.png)
- Make a spreadsheet and copy the spreadsheet ID from the URL
- Now paste the API key, OAuth Client ID and spreadsheet ID in appropriate places in code
- Run python -m http.server 8000
- Go to localhost:8000 to see the page
