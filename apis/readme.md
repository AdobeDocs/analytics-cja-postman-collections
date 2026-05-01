# Adobe Analytics and CJA API Postman Collections
Use the Postman collections in this repository to work with public Adobe Analytics 2.0 
and Customer Journey Analytics APIs.

## CJA Postman collection
The CJA Postman collection covers the full CJA API surface — 61 endpoint requests across 
14 API groups, including Reporting, Dataviews, Connections, Segments, Calculated Metrics, 
and more.

## Environment setup
Import the included `postman_environment.json` template into Postman alongside the 
collection. Then populate the following variables with values from your CJA integration 
on the [Adobe Developer Console](https://developer.adobe.com/console) or the 
Get credentials feature on the [CJA API Reference](https://developer.adobe.com/cja-apis/docs/api):

| Variable | Description |
|---|---|
| `ACCESS_TOKEN` | Bearer token for authorization |
| `API_KEY` | API key from your integration |
| `IMS_ORG` | Your organization ID |
| `BASE_URL` | Set to `https://cja.adobe.io` |

## Authorization token
Generate an access token in the Console or using the Get credentials feature on the 
[CJA API Reference](https://developer.adobe.com/cja-apis/docs/api). Click **Generate**, 
copy the token value, and paste it into the `ACCESS_TOKEN` variable in your Postman 
environment.
