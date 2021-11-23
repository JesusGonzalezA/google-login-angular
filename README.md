# SampleAuthentication

Following the blog post: https://levelup.gitconnected.com/how-to-sign-in-with-google-in-angular-and-use-jwt-based-net-core-api-authentication-rsa-6635719fb86c

## Installation

1. Download angular cli
```bash
npm install -g @angular/cli
```

2. Download dependencies
```bash
npm install
```

## Run the application

1. Run the server
```bash
ng serve
```

Now the application should be visible on http://localhost:4200/

2. Open the console in the developer tools of your favourite browser
3. Click on "Sign in with google"
<img width="908" alt="Captura de pantalla 2021-11-23 a las 16 55 09" src="https://user-images.githubusercontent.com/51116828/143047459-28d09a45-b7f4-4d43-a7fd-e9f098e03e47.png">
4. You'll see a "SocialUser" object printed on the console. We'll use the property "idToken" to validate the token in our backend application.
