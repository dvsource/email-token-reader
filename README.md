# Email Token Reader

1. Read Latest email via Gmail API
2. Get token code from the email subject
3. Store it to the clipboard

### Create credential.json

- Go to https://console.cloud.google.com/
- Create a new project or Use a existing one
- Enable Gmail API
- APIs & Services > Credentials.
- Create Credentials > OAuth client ID.
- Application type > Web application.
- Download client_secre_xxxx.json and rename to `credential.json`

- refer: https://developers.google.com/workspace/guides/create-credentials#oauth-client-id

### Run

First create credential.json

> `node app.js`

### TODO

- [ ] Replace first email read with a proper filter
- [ ] Make a executable

#### Windows shortcut Tip:

Clone project

```
mkdir C:\src
git clone https://github.com/dvsource/email-token-reader.git
cd email-token-reader
touch credential.json
```

Create shortcut with

```
cmd.exe /K "cd C:\src\email-token-reader && node app.js"
```
