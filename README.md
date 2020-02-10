# NodeJS Web App secured by Azure AD.

## See other Azure AD + NodeJS code examples

1. Daemon/serverless applications [Client Credential Flow](https://github.com/maliksahil/ms-identity-nodejs-client-credential-flow)
2. Web Applications [OIDCStrategy](https://github.com/maliksahil/ms-identity-nodejs-webapp)
3. Web APIs [BearerStrategy] (https://github.com/maliksahil/ms-identity-nodejs-webapi)
4. Forwarding user identity [On Behalf Of Flow] (https://github.com/maliksahil/ms-identity-nodejs-on-behalf-of)
5. Key Vault and [Managed Identity] (https://github.com/maliksahil/ms-identity-nodejs-managed-identity)

## App setup and configuration
1. Register a web app
2. Redirect URI of `http://localhost:3000/auth/openid/return`
3. Enable id_token
4. Add a client secret, note down it's value.
5. Update values in config.js
6. Run `npm start`, and visit `http://localhost:3000` in your favorite browser.