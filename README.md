# Adobe Analytics and CJA API Postman Collections

Use the Postman Collections on this repository to work with public Adobe Analytics 2.0 and Customer Journey Analytics APIs. 

## CJA Postman collection

The CJA Postman collection covers the full CJA API surface — 61 endpoint requests across 14 API groups, including Reporting, Dataviews, Connections, Segments, Calculated Metrics, and more.
  
## Environment setup

When you create an API integration project on the [Adobe Developer Console](https://developer.adobe.com/console), click the **Export Details to Postman** button to generate a pre-filled Postman environment file. This file contains your credential values, including:

- `API_KEY`
- `IMS_ORG`
- `TECHNICAL_ACCOUNT_ID`
- `CLIENT_SECRET`
- `SCOPES`

Once you download and import the file into Postman alongside your CJA collection, the variables become automatically populated. 

Alternatively, you can copy the header values from the Console or the Get credentials feature on the [CJA API Reference](https://developer.adobe.com/cja-apis/docs/api) and paste them into the [Postman Environment Template](Postman Environment Template.postman_environment.json) on this repository. You can also paste them directly into Postman, according to the structure you have set up in the tool.

## Authorization token

Generate an authorization token in the Console or the Get credentials feature on the CJA API reference. Click the **Generate** button in the Console or on the API reference page. Copy the token value and paste it into the `ACCESS_TOKEN` variable in your Postman environment.


