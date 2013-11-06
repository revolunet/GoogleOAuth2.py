# GoogleOAuth2.py

A simple class to handle the Google Oauth2 process easily and integrate in your Python applications.

## Usage

```python
CLIENT_ID = "1233459634.apps.googleusercontent.com"
CLIENT_SECRET = "zegezc8MADUzrgZ3Wo_hy23"
auth = GoogleOauth2(CLIENT_ID, CLIENT_SECRET)
token = auth.get_token()
```

## Features

 - You can add a `callback` parameter to the `get_token` method to handle the token input differently than console and raw_input (default).
 - The `GoogleOauth2` `store` parameter can be None or a filename or fullpath where to store the credentials.
 - Refreshable tokens are automatically refreshed when stored.
 - require oauth2client module

## Licence

Licensed as MIT
