# Laxmi Catering — website + Android source starter

This package contains:
- `website/`: standalone bilingual website / PWA-ready static files
- `android/`: Android Studio project wrapping the same local website in a WebView

Business contact configured: **9441009600** (WhatsApp uses India country code +91).

## Try the website
Open `website/index.html` in a browser. Some browsers restrict local features when opening files; for the best test run a local static server or publish the `website` folder.

## Build Android app
1. Install Android Studio (current stable) and a compatible JDK.
2. Open the `android` folder as an existing project.
3. Allow Gradle sync; install Android SDK Platform 35 if prompted.
4. Run on an emulator or Android phone. To create an installable APK, use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Before public release, set a final app icon, confirm app name/package ID, test on physical devices, and create a signed release build.

## Not yet production-ready
This is a runnable starter, not a hosted website or built APK. Demo menu and orders are saved in local browser storage on each device, not in a shared server. Admin access is not secured. WhatsApp opens a pre-filled message that the user sends manually. Prices are examples. No payments, order notifications, cloud sync, or database are connected.

## Steps still required for a real launch
- Confirm final menu, portion sizes, prices, service area, business details and Telugu wording.
- Add secure backend/database, admin login/roles, validation, backups and privacy/security controls.
- Add a privacy policy and terms, and check applicable local business/food registration requirements.
- Host website on a domain with HTTPS; connect backend environment variables and test forms.
- Build and sign Android APK/AAB; if distributing through Google Play, complete Play Console account, store listing, data safety declarations and review.
- Test ordering, WhatsApp handoff, accessibility, Telugu rendering, offline/error states, and customer-data handling.
