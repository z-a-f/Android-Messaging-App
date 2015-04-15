# Android-Messaging-App
Basic messaging app using Sinch API - After building, install on two different devices (or 
emulators), login with any username (no password), put the other login in the "recipient" field, 
and send the message.

### Where do I put my app keys and secrets?
Create file `res/values/secret.xml` with the following content (from Sinch.com):
```XML
<?xml version="1.0" encoding="utf-8"?>
<resources>
	<string name="APP_KEY">_your_app_key_</string>
	<string name="APP_SECRET">_app_secret_</string>
	<string name="ENVIRONMENT">_environment</string>
</resources>
```

### Notes
* As of April 15, 2015 Sinch doesn't support x86, so you'll have to use ARM emulator
* All credit goes to https://www.sinch.com/

### TODO
