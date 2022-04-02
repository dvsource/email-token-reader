# Email Token Reader

1. Read Latest email via Gmail API
2. get token code from the subject
3. store it to the clipboard

### create credential.json

- https://console.cloud.google.com/
- APIs & Services > Credentials.
- Create Credentials > OAuth client ID.
- Application type > Web application.
- download client_secre_xxxx.json

- refer: https://developers.google.com/workspace/guides/create-credentials#oauth-client-id

### TODO

- [ ] replace first email read with a proper filter
- [ ] make a executable
