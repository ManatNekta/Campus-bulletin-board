# ORBIT

Connecting our campus, one post at a time. A community bulletin board built with plain HTML, CSS and JavaScript (no frameworks).

## Files
- `index.html` structure and content
- `style.css` all styling
- `script.js` all functionality

## Run locally
Extract the folder first, then open `index.html` in Chrome. If sign-in fails, serve the folder instead: `python -m http.server 8000`, then visit http://localhost:8000. Works on GitHub Pages (https).

## Limitations
There is no server or database. Accounts, posts, comments, likes, registrations, notifications and uploaded images are stored in the browser's local storage only, so data is not shared between devices or people, is lost if browser data is cleared, and is limited to about 5 MB. Passwords are hashed in the browser, which is not real server-side security, and admin and member permissions are enforced by the app's code, not a backend. A real deployment needs a backend such as Supabase or Firebase.

Demo logins: admin@demo.test / Admin123! and member@demo.test / Member123!

Images are illustrations drawn in JavaScript, so there is no assets folder. Fonts (DM Sans, DM Serif Display, Cinzel Decorative, Cormorant Garamond) load from Google Fonts and fall back to system fonts offline.
