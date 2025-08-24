Aqua Alert — Aero Edition (Node + Express + SQLite)
--------------------------------------------------

How to run (server + client):
1. Open terminal, go to server folder:
   cd server
   npm install
   npm start

   This creates server/aqua_alert.db and seeds users:
     - manager / pass123
     - resident / pass123

2. Open client/index.html in a browser (double-click). The frontend calls http://localhost:5000/api/

Notes:
- messages are stored in server/aqua_alert.db (SQLite). Use DB Browser for SQLite to view/manage.
