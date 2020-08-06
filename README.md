# OpenID Connect Sample in Node.js

This is a sample application showing how to configure and enable OpenID Connect middleware in a Node.js web application with Express, openid-client and Passport.

## Pre-requisites
* NodeJS
* GIT command line
* Supported IDE e.g. Visual Studio Code

## Installation

To install this sample application, run the following commands:

```console
$ git clone https://github.com/EnsurityTechnologies/XSense-Node-OIDC-Client.git
$ cd XSense-Node-OIDC-Client
$ npm install
```

This will get a copy of the project installed locally, along with all of its dependencies.

## Setup

Update `app.js` client attributes. The sample values are shown below.

```
client_id: 'nodejs_demo',
client_secret: 'j9wYVyD3zXZPMo3LTq/xSU/sMu9/shiFKpTHKfqAutM=',
redirect_uris: ['http://localhost:3000/auth/callback'],
post_logout_redirect_uris: ['http://localhost:3000/logout/callback'],
token_endpoint_auth_method: 'client_secret_post'
```

> granttype : Autorization_Code

## Run the Site

Now that you've got the setup done, you need to run the site.

Run the actual website locally:

```console
$ npm start
```

## Test the site

Finally, open the browser, visit [http://localhost:3000](http://localhost:3000)
and test out the site!
