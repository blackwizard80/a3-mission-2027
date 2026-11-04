A3 MISSION 2027 – Android installable study planner

Files:
- index.html: app
- manifest.webmanifest: install metadata
- sw.js: offline cache

Install on Android:
1. Upload these three files to an HTTPS static host (for example, your own GitHub Pages site).
2. Open the hosted index.html in Chrome on Android.
3. Chrome menu (⋮) > Install app / Add to Home screen.
4. Open it from the new home-screen icon.

Data:
- To-Do, timetable, and study-time records are stored in browser localStorage.
- Notes and photos are stored in IndexedDB on this phone/browser.
- Clearing Chrome site data can erase this information. Export/backup is not yet included.
- This is an installable PWA, not a Play Store APK.
