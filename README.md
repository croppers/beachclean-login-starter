# Beach Cleanup App with Login Kit

This application is an adaptation of the original project, "MLH Digital Ocean Workshop" created by esouthren. In this version, the application has been modified to include integration with Snapchat, enabling custom e-mail messages to be sent to users, and a personalized user interface.

Link to esouthren's GitHub: https://github.com/esouthren.

Link to MLH Digital Ocean Workshop: https://github.com/MLH/mlh-localhost-digital-ocean-starter

# Tech used in this project

## NodeJS (https://nodejs.org/)
NodeJS is an open-source framework rooted in Javascript that can be used to build web applications.

## NPM (https://www.npmjs.com/)
NPM (Node Package Manager) is a way to manage certain common packages for NodeJS. This app takes advantage of Express and Request, two common packages for node.

## SmtpJS (https://smtpjs.com/)
SmtpJS lets you send an e-mail using the SMTP protocol, all from the comfort of your own Javascript file :)

## Snap Kit (https://kit.snapchat.com/)
Snap Kit is the set of developer tools for Snapchat integration. Specifically, this application uses Login Kit to enable Snapchat logins and profile data retrieval.

# How to launch the app
The instructions that follow explain how to deploy the app locally...

1. Ensure that NodeJS and NPM are installed on your computer.
2. Obtain an API Key from Snap Kit, with Login Kit enabled.
3. Replace the default API Key in "app.js" line 10.
4. In command prompt, type the below commands...

```
$ cd ../beachclean-loginkit
$ npm install
$ npm start
```

5. Navigate to https://localhost:3000 to view the app!
