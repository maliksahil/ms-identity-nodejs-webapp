# NodeJS Web App secured by Azure AD.

## App setup and configuration
1. Register a web app
2. Redirect URI of `http://localhost:3000/auth/openid/return`
3. Enable id_token
4. Add a client secret, note down it's value.
5. Update values in config.js
6. Run `npm start`, and visit `http://localhost:3000` in your favorite browser.