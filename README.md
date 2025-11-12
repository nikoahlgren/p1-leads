# Micro CRM Leads (Project 1)
## Live Deployment
Live: https://p1-leads-kqrt.onrender.com # Replace this with your application's public URL
## Running Locally
### Prerequisites
You must have Node.js (version 18 or later) installed.
### Setup Instructions
# 1. Install dependencies defined in package.json
npm install # Reads package.json and installs all required packages into node_modules/
# 2. Start the server - opens on http://localhost:3000/ by default (or the PORT from .env)
npm start # Executes the "start" script defined in package.json
## API Endpoints
GET /api/leads # Retrieves a list of all leads. Optional query parameters: ?q= (search), &status= (filter by status)
POST /api/leads # Creates a new lead. Requires: name, email. Optional: company, source, notes.
PATCH /api/leads/:id # Updates an existing lead by ID. Fields to update: status, notes.
## Technology Stack
Node, Express, vanilla JS, JSON file storage.
## Project Reflection (for coursework)
a few notes:
- Quite alot of new things for me. JS and Node. I also had a little refresh in git which is nice. Project overall seems quite straight forward. Also was cool to use render.com. I have not used it before.
- It was nice to look at the comments and follow the flow of code. especially middleware was a learning moment.
- After analyzing and testing i noticed that the leads.json is used as the database. Multiple concurrent writes from different processes could cause race conditions possibly.
- Maybe this could use a SQLIte database if we wanted to improve this.
  

