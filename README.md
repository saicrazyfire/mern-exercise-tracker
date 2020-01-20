## Learning the MERN stack

(MongoDB + Express + React + Node.js)

|                                                       |                                                                                                                        |                                                                     |
| ----------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [Video](https://www.youtube.com/watch?v=7CqJlxBYj-M&) | [Blog](https://medium.com/@beaucarnes/learn-the-mern-stack-by-building-an-exercise-tracker-mern-tutorial-59c13c1237a1) | [Code](https://github.com/beaucarnes/mern-exercise-tracker-mongodb) |

---

Pre-requisites:

- Node.js version 8.17.0 (lts/carbon)
- Nodemon - Install `nodemon` globally or use `npx nodemon`.

> **Note:** You will need to run `sudo npm install -g --force nodemon` to get macOS terminal to find nodemon.

> **Tip:** To run the backend `server.js` file, you may run `npx nodemon server` without modifying the `package.json` file.

---

## Creating the project

1. Run `npx create-react-app mern-exercise-tracker` to create the folder/React project

## Setting up the backend

2. Change directory into newly created folder `cd mern-exercise-tracker`
3. Create new folder `backend` and change into it
4. Run `npm init -y` to create npm scaffold project with default values
5. Create a new file called `server.js`
6. Paste boilerplate express code with mongoose/cors/dotenv lines
7. Create `.env` file in backend folder and make sure the mongoose URI is set properly (note: make sure to change URI to `localhost` if running locally).
8. Make sure the root `.gitignore` file is skipping the newly created `.env` file and the `node_modules` folder within the backend folder
9. In the backend folder, create a new folder called `models` with two files `exercise.model.js` and `user.model.js`
10. Input the schema into each respective model file
11. In the backend folder, create a new folder called `routes` with two files `exercises.js` and `users.js`
12. Update `server.js` to use the newly created routes
13. Input the routes into the newly created routes files. Include advanced features like update by ID and deleting exercises

### Done with backend!

You are done with the backend (for the video section)! Skip to 43:37 in the video to proceed with the frontend

---

## Setting up the frontend

### _TBD_
