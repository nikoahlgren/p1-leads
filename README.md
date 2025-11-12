# Micro CRM Leads (Project 1)

## Live Deployment
Live: https://p1-leads-kqrt.onrender.com // The public URL where the live application can be accessed (from Render).

## Run Locally

### Setup Instructions
npm install // Installs all project dependencies defined in the package.json file.
npm start // Executes the "start" script defined in package.json (e.g., node server.js).
Open http://localhost:3000/ // Instructs the user where to access the application in their browser.

## Features
- Create and list leads
- Filter by status and search by name or company
- Update status

## Windows and macOS Notes
Open VS Code terminal. The commands are the same on both platforms.

## Reflection (Required for Marking)
a few notes:
- Quite alot of new things for me. JS and Node. I also had a little refresh in git which is nice. Project overall seems quite straight forward. Also was cool to use render.com. I have not used it before.
- It was nice to look at the comments and follow the flow of code. especially middleware was a learning moment.
- After analyzing and testing i noticed that the leads.json is used as the database. Multiple concurrent writes from different processes could cause race conditions possibly.
- Maybe this could use a SQLIte database if we wanted to improve this.
  

