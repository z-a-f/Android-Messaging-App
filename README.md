# Android-Messaging-App
Basic messaging app using Sinch API

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