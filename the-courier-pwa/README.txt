THE COURIER — WEBSITE / PWA PROTOTYPE
School: Eastern Samar National Comprehensive High School

FILES
- index.html: responsive publication website with Home, Feature Stories, Sports News, Editorial Cartooning, About, and browser-local content manager
- manifest.webmanifest: installable PWA metadata
- sw.js: basic app-shell service worker for HTTP/HTTPS hosting
- assets/courier-logo.png: supplied publication logo
- assets/layout-reference.png: supplied visual reference (not shown in the live UI)

PREVIEW
Open index.html in a modern browser. For PWA/service-worker features, serve the folder from localhost or an HTTPS host (service workers do not run from file://).

CONTENT MANAGER
Choose “Admin CMS” in the navigation to add/edit/delete feature stories, sports reports (set category to Sports), and editorial cartoon entries. Data is stored in this browser using localStorage. “Export content backup” downloads a JSON backup.

IMPORTANT LIMITATIONS
This is a front-end prototype, not a secure production CMS. There are no logins, server database, multi-user access, hosted image uploads, or server-side publication controls. LocalStorage data remains on the browser/device where it was entered. For a real school publication, deploy on HTTPS and connect a secure backend/CMS with editor authentication, backups, moderation, and privacy safeguards. Replace all sample copy and placeholder images with verified, school-approved material before launch.
