MAXEARN ZONE — Full-stack starter

Run:
1) Install Node.js 18+.
2) Open terminal in this folder.
3) Run: node server.js
4) Open: http://localhost:3000

Data is stored in data/db.json for this self-contained starter. For production, migrate the data layer to PostgreSQL/MySQL and add HTTPS, CSRF protection, rate limiting, backups, payment-provider webhooks and KYC/compliance as required.

Create the first admin once:
POST /api/admin/bootstrap with JSON {"name":"Admin","phone":"01XXXXXXXXX","password":"change-me"}
Then log in through the normal login form.
