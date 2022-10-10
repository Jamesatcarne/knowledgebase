# Knowledge Base App

This app is designed as a project to teach web development. The app is made using the following technologies:

#### Frontend

- React & Create React App
- Tailwind CSS
- AXIOS

#### Backend

- Firebase Auth
- Firebase Firestore Database
- Firebase Hosting

#### Other

- GitHub with GitHub Flow
- GitHub Actions CICD

## Getting set up

Before starting we need to install some dependancies. We will need:

- Nodejs LTS from [https://nodejs.org/en/]
- Git from [https://git-scm.com/downloads]
- A GitHub account set up here [https://github.com/]
- VS Code installed from here [https://code.visualstudio.com/]

Once you have each of these you can create your new app. To do this open a terminal inside a folder where you will be saving your app, and type the
following: npx create-react-app knowledge-base-frontend

You will likely get a prompt asking you if you are ok with the terminal installing some packages. Agreet to this (type y and press enter). You will then see
some text in the terminal indicating the install is taking place. It will take up to a couple of minutes to complete. Once done you will have a new folder
called knowledge-base-app, and inside this folder you'll see a collection of subfolders and files. This is your basic React app.

Open the new folder inside VS code. Open a terminal in VS code. And type: npm run start. This will fire up the react app. If all is well you should see a
message confirming that the app is running, and your default browser will open a screen at location localhost://3000 showing the create-react-app logo.

Congratulations. You now have your default React project set up and you are ready to begin developing your frontend app.

The next steps should be to:

- Remove the unecessary files made by Create React App
- Edit the files left to the minimum necessary
- Install the following dependancies via NPM
  - Tailwind CSS (Allows us to create easy styles for the user interface)
  - React Router V6 (Allows us to move the user around the website in a flexible way)

## Structure of the App

The front end of the app is built using React. It has the following pages:

- Home page that displays for users until they are logged in. Unauthorised users will not be able to get past this page.
- List page that shows all your knowledge base articles.
- Reader page that allows you to read a specific knowledge base article.
- Creator page that allows you to build a new knowledge base article.
