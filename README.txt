SUSHANT YADAV — REAL-LIFE FINAL BUILD

REQUIREMENTS
- Node.js 24 LTS recommended (Node 22.5+ required for node:sqlite).
- No npm packages are required. npm install is NOT required.
- macOS/Linux servers need the unzip command for ZIP website uploads.

LOCAL START
1. Open Terminal.
2. cd to this folder. Example:
   cd ~/Desktop/timepass/Sushant_Yadav_Real_Life_FINAL
3. Start:
   node server.js
4. Open http://localhost:3000
5. Admin: http://localhost:3000/admin

DEFAULT ADMIN
Username: admin
Password: Sushant@123
CHANGE THIS IMMEDIATELY from Admin -> Security.

FEATURES
- Premium responsive portfolio website
- SUSHANT YADAV profile and +9779820221555
- Server-side SQLite database using Node's built-in node:sqlite
- Secure-ish scrypt password hashing and signed-in-memory sessions
- Login rate limiting
- Profile, services, pricing and appearance management
- Customer enquiry database + status management
- Visit counter
- Portfolio upload/edit/delete
- Full HTML/ZIP website hosting with CSS/JS/images preserved
- ZIP path/symlink/file-count/extracted-size safety checks
- Backup export and restore
- Admin password change
- Reset data

IMPORTANT FOR INTERNET DEPLOYMENT
- Use HTTPS via a reverse proxy such as Caddy/Nginx.
- Set ADMIN_USER and a strong ADMIN_PASS only for first setup, and set a long random ADMIN_SECRET.
- Put the app behind a firewall and keep Node updated.
- Back up data/sushant.db and uploads/ regularly.
- Do not upload untrusted/malicious websites. Uploaded HTML/JS is intentionally served as websites.
- For production email notifications, connect an email provider separately.
