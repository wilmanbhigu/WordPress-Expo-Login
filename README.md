# WordPress-Expo-Login
Example Expo React Native App using WordPress OAuth2 Server for login.

### How to use:
1. Install WordPress OAuth Server plugin: https://wordpress.org/plugins/oauth2-provider/
2. In WP OAuth Servers settings enable OAuth Server.
![WP OAuth Server Settings](https://i.imgur.com/cMWCvS8.png)
3. Under Clients create a new client.
  - Choose Authorization Code grant type.
  - Name your client.
  - Don't worry about Advanced Settings
4. Copy your Client ID
5. In `screens/SignInScreen.js` add your client id where it says `CLIENT_ID = 'INSERT-CLIENT-ID';`
6. Change example.com to your WordPress websites url on the sign in screen as well.
7. Log in to your app using WordPress!
