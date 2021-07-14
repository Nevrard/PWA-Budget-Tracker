# PWA-Budget-Tracker


# Table of Content
*[General information](#general-information)

*[Specifications](#specifications)

*[Screenshots](#screenshots)

*[Deployment](#deployment)


## General information
Budget Tracker is a progressive web application that allows users to track their budgets by adding expenses and deposits to their budget through the "Add/Subtract Funds" buttons. They are able to add a transaction with or without a connection. When a user enters a transaction while offline, these transactions are stored in the indexedDB, and transferred to the database when the user comes back online.

## Specifications

The application is Built using following tools and languages :

 -Node.js

 -Javascript

-MongoDB

-IndexedDB - (https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

-Webmanifest - (https://developer.mozilla.org/en-US/docs/Web/Manifest)

-Progressive Web Apps - (https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
MongoDb

To run the apllication ,type "node server.js" in your terminal

## Screenshots

Online 

![image](https://user-images.githubusercontent.com/77184762/125553147-52c01959-18d8-4d8c-8850-e4a28f1e730f.png)


Offline

![image](https://user-images.githubusercontent.com/77184762/125559699-fbb3c047-115a-4edb-baf4-8d64a3e442e9.png)

When a new transaction is added while offline , It is saved in indexedDB. When back online ,the transaction is loaded in the Database and wiped from the indexedDB

![image](https://user-images.githubusercontent.com/77184762/125559906-52753e1b-ed45-4e46-9183-987298d6546d.png)


## Deployment

Users can view the deployed project [here](https://budgettrackersoft.herokuapp.com/). 
If you intend to iterate on the project, besides downloading the repo to your machine, be sure to run npm i in the root directory and to also have MongoDB installed and ready.
-Clone the repository on your local device and open Terminal or Bash
-In Terminal or Bash, the user will run the following command to download all application dependencies: "npm install"
-In Terminal or Bash, the user will run the following command to run the application: "npm run start"
-Once the command is run, a successful message will appear "App running on http://localhost:3000"
-In your browser, type "http://localhost:3000/"



