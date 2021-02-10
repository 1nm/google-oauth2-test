# Google Calendar API OAuth 2.0 Demo

Retrives 10 upcoming events

Based on the [complete example](https://developers.google.com/identity/protocols/oauth2/web-server#example) in "Using OAuth 2.0 for Web Server Applications" documentation.

Note that the refresh token is only accessible for the first time that the user grants the access.

See https://github.com/googleapis/google-api-python-client/issues/213#issuecomment-205886341

## How to run

Put your client secret in `client_secret.json`

```
pip install -r requirements.txt
python3 server.py
```

Go to http://localhost:8080

Click `Test the auth flow directly`


