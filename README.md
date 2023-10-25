# iTwin command line application

This is a sample code to demonstrate how to make query to an iModel by downloading a briefcase. The sample code is written for JavaScript backend apps and require Node.js to run it. The sample code is written in TypeScript and uses the iModel.js library.

## Environment variables

Update the .env file present in the root folder of this repository. The following environment variables should be updated along with their respective values in the .env file.

```text
ITWIN_VIEWER_SCOPE ="imodels:read"

ITWIN_VIEWER_CLIENT_ID=""

ITWIN_VIEWER_REDIRECT_URI="http://localhost:3000/signin-callback"

ITWIN_VIEWER_ISSUER_URL="https://ims.bentley.com"

IMJS_ITWIN_ID=""

IMJS_IMODEL_ID=""
```

## Install dependencies

npm install

## Run the app

npm start
