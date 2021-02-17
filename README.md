# About

This is the base template for creating Simple React app with express server by extending [Create React App](https://github.com/facebook/create-react-app) webpack configurations.

If you don't specify a template (for example, `--template with-express`), Simple React app will be created by default.

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.

# Install

`npx create-react-app <your-app-name> --template with-express `

# Command

<b>Don't do yanr start. Instead, refer to the following commands.</b>
Navigate to `your-project` by `cd your-project` and run the following commands:

- To `Run Server` - <b>npm run server</b> or <b>yarn run server</b>
- To `Run Client` - <b>npm run client</b> or <b>yarn run client</b>
- To `Run Server with Client` - <b>npm run server-with-client</b> or <b>yarn run server-with-client</b>

# Development

- For developing frontend app, go to the frontend folder using `cd frontend` command and continue your development as you would do for your traditional frontend app.
- For developing backend app, go to the backend folder using `cd backend` command and continue your development as you would do for your traditional backend app.
- To view frontend app, go to [http://localhost:3000](http://localhost:3000)
- Backend is hosted at [http://localhost:9000](http://localhost:9000)
- To change the port of your backend app, navigate to `backend/bin/`, open <b>www</b> and change port to your desirable port at <b>line 15</b>. Make sure to change your proxy object in your frontend <b>package.json</b>.
