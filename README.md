# DevRadar

## The purpose
It's a mobile and web application with back-end developed with Node.js and Front-end with React. It's a POC application that you register a developer with the github user, technologies and geolocation. This application uses the github api.
The application is in Brazilian Portuguese.

## How to Execute
It's possible to execute the project as follow:

Back-end:
1- `cd backend` - to access the backend directory

2- `yarn` - to execute the installation of the libs

3- `yarn dev` - to run the developer server

Web application: 
1- `cd web` - to access the web directory

2- `yarn` - to execute the installation of the libs

3- `yarn start` - to start the web application

Web application: 
1- `cd mobile` - to access the mobile directory

2- `yarn` - to execute the installation of the libs

3- `yarn android` - to start the android application

## Features

Web Application:

![Web application](https://github.com/Gisleude/DevRadar/blob/master/public/web-application.png)

(1) Register developer - You can put the github user and some technologies, the geolocation is autofilled, but you can modify it.

(2) List developers registered - You can see all the developers registered.

Mobile Application:

(1) Find developers near you - You can find developers near you based on your device location and based on the techs that you fill on the search.

![Find developers](https://github.com/Gisleude/DevRadar/blob/master/public/find-devs.png)

(2) Developer Overview - You can click on the developer and the app will show an developer overview.

![Developer Overview](https://github.com/Gisleude/DevRadar/blob/master/public/dev-overview.png)

(3) Link with Github - You can click on the overview to open the developer github page.

![Developer Github](https://github.com/Gisleude/DevRadar/blob/master/public/dev-github.png)

## Observations
● This application was creating using Expo, so you need to install the Expo on your device before.

● You need to change the password and the db name on the backend/src/index.js to your credentials

● You need to allow the geolocation in your browser to the site autofill the input

● This application was created on the Omnistack Week Course at Rocketseat.