# local_passport_website

Small website demo that uses Passport local strategy and EJS views for login/register/profile pages.

Dependencies
- express
- passport
- passport-local
- express-session
- mongoose
- ejs
- bcryptjs

Setup
1. Install dependencies: `npm install`
2. Start the site: `node app.js`
3. Open the routes in the browser (see `views/` for templates: `login.ejs`, `register.ejs`, `profile.ejs`).

Notes
- Ensure the auth service or configuration matches the passport setup in `config/passport.js`.
