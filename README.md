# CommunityHub :heartpulse:
#### A small, community-based, lightweight image-sharing platform. Users can visit the gallery, browse images, and upload images of their own. :camera:

### Setup

1. Clone/download repo to local machine.
2. If necessary, unzip the downloaded folder.
3. Open the project folder `firegram` with your terminal of choice and run `npm i` to install dependencies.
4. In order to run locally, a Firebase project must be setup for the app. [Set one up.](https://firebase.google.com/) Analytics is not necessary.
5. Once the Firebase project is provisioned, enable both Storage and Firestore Database services for the project. These will hold images and references.
6. Create a web app for the project, this can be done from the main Project Overview page. Save the API keys and other credentials for this application.
7. Create a `.env.local` (or `.env.prod` for production) and populate the `REACT_APP_` prefixed variables with your Firebase credentials.
8. Run `npm start` to run the project locally using the `.env.dev` credentials. 
9. Run `npm build` to package the app into a static `build` folder for hosting.

### TODOs

* :lock: Set-up authentication so not just anyone can upload images, otherwise setup some safeguards to what gets uploaded/displayed
* :man_student: Create about and profile pages if necessary
* :green_book: Break images into categories so there's not just one large, general gallery
* :star2: Style the application a bit more, maybe integrate Tailwind/Bulma

