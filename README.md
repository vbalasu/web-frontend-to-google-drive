# web-frontend-to-google-drive

Use this boilerplate code as a starting point for a frontend web application that uses Google Drive for storage

Please be sure to supply your own value for `client_id`.

The code consists of a `getToken` method that authorizes the application to access the user's Google Drive (Scope: `https://www.googleapis.com/auth/drive.file`)

The `putFile` method writes some data to a new file on Google Drive.

The `getFile` method retrieves this file and shows its contents on the page.

The accompanying `package.json` contains a helper script to deploy the resulting [index.html](src/index.html) to an S3 bucket for static serving.

You can view the resulting page [here](https://cloudmatica.s3.amazonaws.com/web-frontend-to-google-drive/index.html)