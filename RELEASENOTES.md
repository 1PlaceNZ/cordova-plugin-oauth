# Release Notes

### 4.0.1 (23 September 2022)

Merged https://github.com/AyogoHealth/cordova-plugin-oauth#8bb0c03dae87baf8484ad187d7a28255f767658b into main
Merged https://github.com/AyogoHealth/cordova-plugin-oauth#8bb0c03dae87baf8484ad187d7a28255f767658b into feature/OpenID
### (24 August 2022)

Changed the returned message with the JSON object containing all of the key/value pairs from the OAuth redirect query string to having the JSON object contain the `url` field with the redirect query string.
This change was made to support OpenId responseMode fragment response.  The plugin was returning an empty JSON object.  This allows the cordova app to parse the redirect query string.
