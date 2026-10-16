DYFOS local HTML website
Open index.html using a local server. Navigation pages are separate HTML files in this folder. Add each page content inside its main section. Keep wp-content folder beside the HTML files for images, CSS, and theme assets.
Run: python -m http.server 8000 then open http://localhost:8000/

Member panel demo: Register from the header first, then login with that email/password. Successful login opens admin-panel.html. The panel redirects to index.html if the current browser tab has no successful login session. This is client-side gating only; static HTML/localStorage cannot provide real security or admin authorization. Use a backend/database and server-side authentication before public deployment.
