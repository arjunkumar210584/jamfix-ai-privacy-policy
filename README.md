# Privacy Policy — JAMFIX

**Effective date:** [Day Month Year, e.g. 11 October 2026]  
**App name:** JAMFIX  
**Android application ID:** `jam.fix`  
**Developer / data controller:** [Your legal name or company name]  
**Contact:** [your-email@example.com]

---

## 1. Introduction

JAMFIX (“we”, “our”, “us”) is a mobile navigation and traffic-aware routing application. This Privacy Policy explains what information we collect, how we use it, who we share it with, and what choices you have. By using JAMFIX, you agree to this policy.

If you do not agree, please do not use the app.

---

## 2. Information we collect

### 2.1 Account information

If you sign in with **Google**, we receive and use:

- Your **Google account identifier** (Firebase Authentication user ID)
- Your **email address** (used as your account identifier in the app)
- **Display name** and **profile photo URL** (if provided by Google)

We do not receive your Google password.

### 2.2 Location information

JAMFIX needs location to provide maps, routing, turn-by-turn guidance, commute learning, and traffic-related features. Depending on permissions you grant:

- **Precise location** while you use the app (foreground)
- **Background location** (only if you allow it) for navigation and related alerts while the app runs in the background

Location is used to calculate routes, show your position on the map, estimate arrival times, and support features such as commute learning and traffic intelligence. You can change or revoke location permissions in your device settings at any time; some features will not work without location.

### 2.3 App data you create or store

We store (on your device and, when you are signed in and cloud sync is available, in your **Firebase / Firestore account** under your user ID):

- **Preferences** (theme, language, voice and navigation settings, safety and intelligence settings)
- **Saved places** (home, work, custom places)
- **Trip and route-related summaries**, alerts, notifications, and savings records you choose to keep
- **Learned commute patterns** (if commute learning is enabled)
- **Vehicle profiles** (nickname, category, fuel type, efficiency, and vehicle dimensions from our built-in catalog when you select a make/model)
- **Feedback** you submit through the app

By default, **detailed route geometry / precise GPS traces are not stored** unless you explicitly enable options to store route geometry (this is off by default in app preferences).

### 2.4 Voice and microphone

If you enable **voice commands** or related voice features, the app may use the **microphone** to listen for commands on the device. Audio is processed to support in-app voice features; we do not use the microphone unless you enable voice-related permissions and features.

### 2.5 Optional cooperative traffic contribution

If you turn on **“Help improve traffic intelligence”** (cooperative traffic), the app may share **anonymized, coarse speed/traffic-related signals** as described in the in-app setting—not your identity or a continuous raw GPS trace. This setting is **off by default**.

### 2.6 Product analytics (optional)

If **product analytics** is enabled in Settings, we may collect **usage events** through **Firebase Analytics**. Our implementation is designed **not to include precise coordinates** in analytics. You can turn analytics off in **Settings → Privacy and data**.

### 2.7 Crash and diagnostic data

To improve stability, we may collect **crash logs and diagnostic information** through **Firebase Crashlytics** (e.g. stack traces, device model, OS version). This helps us fix bugs. Crash reports are not intended to include your precise location in analytics payloads.

### 2.8 Push notifications

If you allow notifications, we use **Firebase Cloud Messaging (FCM)** to deliver a device token so we can send journey and traffic-related notifications you opt into.

### 2.9 Server-side services (maps, routing, AI)

When cloud features are enabled, your app may call **Google Cloud Functions** and related backends to:

- Compute routes and traffic-aware directions (via Google Maps / Routes services)
- Provide AI-assisted explanations or assistant features (e.g. server-side AI when configured)

These requests are **authenticated to your account** where Cloud Functions and Firebase App Check are configured. Map and routing requests are sent to **Google** as necessary to provide navigation.

---

## 3. How we use information

We use information to:

- Provide navigation, routing, traffic-aware suggestions, and in-app intelligence features
- Sync your library, preferences, vehicles, and trip-related data across devices when signed in
- Send notifications you enable
- Improve reliability (Crashlytics) and understand product usage (Analytics, if enabled)
- Respond to support or feedback you send
- Comply with legal obligations and protect against abuse

We do **not** sell your personal information.

---

## 4. Legal bases (where applicable)

Depending on your region, we rely on:

- **Performance of a contract** — providing the app and navigation services you request
- **Consent** — optional features (analytics, cooperative traffic, background location, microphone, notifications)
- **Legitimate interests** — security, fraud prevention, and improving the app, balanced with your rights

---

## 5. Sharing with third parties

We use service providers that process data on our behalf, including:

| Provider | Purpose |
|----------|---------|
| **Google** (Sign-In, Maps, Navigation SDK, Routes API) | Maps, routing, authentication |
| **Google Firebase** (Auth, Firestore, Functions, Analytics, Crashlytics, Cloud Messaging, App Check) | Account, sync, backend, analytics, crashes, push |

These providers process data under their own terms and privacy policies:

- Google Privacy Policy: https://policies.google.com/privacy  
- Firebase: https://firebase.google.com/support/privacy  

We may disclose information if required by law or to protect rights, safety, and security.

---

## 6. Data retention

- **On-device data** remains until you clear app data, delete specific items in Settings, or uninstall the app.
- **Cloud data** tied to your account remains until you delete it in the app (e.g. clear history, delete learned commute data) or **delete your account** where that option is offered.
- Crash and analytics data are retained according to Firebase/Google retention settings.

---

## 7. Your choices and rights

In the app (**Settings → Privacy and data** and related screens), you can:

- Turn **product analytics** on or off  
- **Export** a copy of your settings (where offered)  
- **Delete** learned commute data, route history, or local data  
- **Pause** commute learning  
- **Sign out** or **delete your account** (where available)

You can also revoke **location**, **microphone**, **notification**, and **background** permissions in Android system settings.

Depending on your country, you may have rights to **access**, **correct**, **delete**, or **object** to processing of your personal data. Contact us at the email above to exercise these rights.

---

## 8. Security

We use industry-standard measures including encrypted connections (HTTPS), Firebase security rules, and App Check where configured. No method of transmission or storage is 100% secure.

---

## 9. Children

JAMFIX is not directed at children under 13 (or the minimum age in your country). We do not knowingly collect personal information from children. Contact us if you believe a child has provided data.

---

## 10. International transfers

Your data may be processed on servers operated by Google/Firebase, which may be located outside your country. Google provides appropriate safeguards as described in their documentation.

---

## 11. Android Auto / in-car displays

If you use JAMFIX with **Android Auto** or similar projection, navigation information may be shown on your car display according to the platform’s rules. The same location and routing data needed for navigation applies.

---

## 12. Changes to this policy

We may update this Privacy Policy from time to time. We will post the updated version at this URL and change the effective date above. Continued use of the app after changes means you accept the updated policy.

---

## 13. Contact

For privacy questions or requests:

**Email:** [your-email@example.com]  
**Developer:** [Your legal name or company name]
