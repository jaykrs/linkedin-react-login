# React Linkedin Login


A simple app to demo Linkedin login using LinkedIn OAuth 2.0


### Install Dependencies

Intall dependencies for server


cd React-Linkedin-Login
npm install



### Get Linkedin App Credential from Linkedin Developer Portal

- client_id
- client_secret

Configure 'http://localhost:3001/callback' as Oauth2.0 redirect uri

### Create Environment Variables

/React-Linkedin-Login/.env


EXPRESS_APP_CLIENT_ID=${Your-Client-ID}
EXPRESS_APP_CLIENT_SECRET=${Your-Client-Secret}
EXPRESS_APP_REDIRECT_URI=http://localhost:3001/callback
```



### Start Server

/React-Linkedin-Login/:


PORT=3001 npm start


## Consumed SDK/API

- [Linkedin OAuth 2.0 (3-Legged)](https://docs.microsoft.com/en-us/linkedin/shared/authentication/authorization-code-flow?context=linkedin/consumer/context)
- [Sign In with LinkedIn](https://docs.microsoft.com/en-us/linkedin/consumer/integrations/self-serve/sign-in-with-linkedin?context=linkedin/consumer/context)


## Disclaimer

This is not an official sample app or documentation from LinkedIn. Please refer to [LinkedIn API Documentation](https://docs.microsoft.com/en-us/linkedin/) for official documentation and sample apps.
