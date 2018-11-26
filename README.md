This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

Initail Setup:
1) Replace: In App.js file
Auth0.configure({
  domain: 'YOUR_AUTH0_DOMAIN',
  clientID: 'YOUR_AUTH0_CLIENT_ID',
  redirectUri: 'http://localhost:3000/',
  responseType: 'token id_token',
  scope: 'openid profile manage:points',
});

2) Replace with your auth0 Domain
const client = jwksClient({
  jwksUri: 'https://YOUR_AUTH0_DOMAIN/.well-known/jwks.json'
});

SetUp the Auth0 account can be found here
https://auth0.com/blog/developing-games-with-react-redux-and-svg-part-3/

Run the project
1. Navigate to server folder
2. open cmd from there 
3. node index.js hit ENTER //this will run your server with auth0 sockets 
4. go to the root 
5. open cmd from here
6. npm start here //this will run the app

Enjoy playing game 
