# node-express-app

> A super simple web app with Node.js and the Express web framework


## Prerequisites

1. Node.js installed
2. npm Node Package Manager (comes with Node.js)


## Install Dependencies Locally

It's easy to install the dependencies so you can run and test your app locally. Open PowerShell here as Administrator, and run: `npm install`. Explore the new node_modules folder.

```PowerShell
npm install
```

## Start App

"Open PowerShell Here as Admin" and start your app with the node command.

```PowerShell
node app.js
```

## Open a Browser Client

Open a web browser. Try these URLs:

1. <http://127.0.0.1:3002/> or <http://localhost:3002/>.
1. <http://localhost:3002/hello>
1. <http://localhost:3002/big>
1. <http://localhost:3002/greeting/42>
1. <http://localhost:3002/yo/Lohita>
1. <http://localhost:3002/yo/Rahul>
1. <http://localhost:3002/yo/Teja>
1. <http://localhost:3002/fortune>

## Modify and Restart Your Node Server

After updating code, use hit CTRL-C CTRL-C to stop your Node server. Restart the server to see your changes.

## OR Use Nodemon

See package.json "scripts" and explore the "run dev" entry. This script starts the server with nodemon ("node monitor") instead of node. Nodemon listens for code changes and restarts automatically. Run a script by calling it with npm:

```PowerShell
npm run dev
```

## Find Your IP address

Open PowerShell as Admin, run ipconfig. Locate your IPv4 address. Invite others on your network to interact with your server-side app.

```PowerShell
ipconfig
```

## Troubleshooting

If you get:

`Error: listen EADDRINUSE: address already in use 127.0.0.1:3002`

There is already an app running on the port. Hit CTRL+ALT+DELETE to see the tasks, and find the running app and Right-click / End Task to kill the current version. Then restart the app.


## Optional: Create an Express app from scratch

1. Create a folder for the app (use lower-case-kebob-case).
1. Add app.js, README.md, and .gitignore.
1. Open PowerShell and run `npm init` to generate package.json.

```PowerShell
npm install
node app.js
```

