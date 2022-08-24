# Release Notes

### (24 August 2022)

Changed the returned message with the JSON object containing all of the key/value pairs from the OAuth redirect query string to having the JSON object contain the `url` field with the redirect query string.
This change was made to support OpenId responseMode fragment response.  The plugin was returning an empty JSON object.  This allows the cordova app to parse the redirect query string.
