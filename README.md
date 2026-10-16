# KasiPower MVP Prototype

**Tagline:** When the lights go out, the community powers up.

A mobile-first Progressive Web App prototype for South African communities dealing with prolonged electricity outages.

## Included
- Home dashboard with a demo outage duration
- Local outage reports, confirmations and restoration status
- Searchable charging / Wi-Fi / backup power directory
- Community requests, offers and notices
- 14-day survival guide with saved checklist state
- PWA manifest and service worker for offline caching
- Responsive design for mobile and desktop

## Important limitations
- All initial outage reports, locations, prices, hours and statuses are fictional demo data.
- This prototype saves reports and community posts in the browser on the current device only. It does not send them to other users or a utility provider.
- No live Eskom/municipal integration, map API, user authentication or private messaging is connected.
- Offline use works after the app has been opened and cached while served over localhost or HTTPS. A phone with no battery cannot run the app.
- The app is a PWA, not an Android APK yet.

## Run locally
A service worker requires localhost or HTTPS. If Python is installed:
1. Extract the ZIP.
2. Open a terminal in the extracted folder.
3. Run `python -m http.server 8080`
4. Open `http://localhost:8080` in your browser.

To test on an Android phone, deploy the folder to a trusted HTTPS host, open the URL in Chrome, and choose **Install app** or **Add to Home screen**.

## Build a real multi-user service
Connect Supabase or Lovable Cloud for authentication and shared database records. Configure access policies before collecting personal data. Use real, verified charging locations and display timestamps on all availability information.

## Android APK
For an installable APK, first publish the PWA on HTTPS and configure valid app icons and a domain. Then use PWABuilder / Trusted Web Activity (TWA), or wrap the project using Capacitor if native features are needed. APK packaging is not included in this ZIP.
