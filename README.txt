PESO POCKET — HOW TO OPEN

1. Extract the ZIP file.
2. Open the "peso-pocket" folder.
3. Double-click index.html to use the tracker in Microsoft Edge or Chrome.

IMPORTANT
- All amount fields begin empty. Example amounts are NOT preloaded.
- Your finance data is saved in your browser on this device using localStorage.
- Use Settings > Export Backup regularly so you can restore your data if browser storage is cleared.
- The tracker works as a normal HTML app when opened directly.
- For installable PWA/offline caching, serve the folder from localhost or an HTTPS website. Service workers do not reliably register from file:// URLs.

SIMPLE LOCALHOST OPTION (Windows)
If Python is installed:
1. Open the peso-pocket folder.
2. Click the folder address bar, type cmd, press Enter.
3. Run: python -m http.server 8080
4. Open http://localhost:8080 in Edge.
5. Edge can then offer Install App from the address bar or menu.
