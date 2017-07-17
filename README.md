# My Stuff

### A Google Cloud Vision + Ionic 3 + Firebase App

Steps to get up-and-running:

1. Create a new Google Cloud project and enable the Vision API by following the instructions here: https://cloud.google.com/vision/docs/before-you-begin.
2. Create an API key: https://support.google.com/cloud/answer/6158862?hl=en. Be sure to review the API key best practices here: https://support.google.com/cloud/answer/6310037.
3. Create a Firebase project by heading over to https://firebase.google.com, clicking Get Started, then the Import Google Project button. Choose the project you created in Step 1.
4. Set the database rules by clicking Database, then the Rules tab. Use the configuration below. Important: This will open up your database so that anyone can both read and write data. In a real world application you will want to restrict this access.
5. Edit /src/environment.ts, adding the configuration values from Steps 2 and 4.

Then
```ionic cordova run android```
or
```ionic cordova run ios```