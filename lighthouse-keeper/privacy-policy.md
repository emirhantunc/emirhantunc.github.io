# Privacy Policy — Lighthouse Keeper

**Effective date:** September 30, 2026
**Last updated:** September 30, 2026

## 1. Who we are and what this policy covers

This Privacy Policy explains how personal data is handled in **Lighthouse Keeper** (the "App"), a single-player game for iOS and Android.

- **Controller / developer:** Emirhan Tunç, an individual developer (referred to as "we", "us" or "our").
- **Contact for privacy questions and requests:** emirhantunc7805@gmail.com
- **Web version of this policy:** https://emirhantunc.github.io/lighthouse-keeper/privacy-policy.html

This policy applies to the App as distributed on the Apple App Store and Google Play. It does not cover third-party websites or services that you reach from an advertisement; those are governed by their own policies.

**In short:** the App has no accounts, no sign-in, no in-app purchases, no analytics or crash-reporting SDK of our own and no server of our own. We, the developer, receive no personal data about you. Your game progress is stored only on your device. The App is free because it shows advertisements through **Google AdMob**, and it is Google, not us, that processes device and advertising data to deliver those ads.

## 2. Information we collect and how it is used

### 2.1 Information you provide directly

**None.** The App does not ask for your name, email address, phone number, photos, contacts, messages or any other content. There is no registration, login, chat or user-generated content.

### 2.2 Information stored only on your device

To let you continue where you left off, the App saves a small game file inside its private storage area on your device. It contains:

- nights completed, stars earned, coins, lamp upgrades, cottage decorations and letters read;
- your settings (music, sound effects, vibration);
- counters used to space out advertisements (for example, how many nights have passed since the last full-screen ad and how many free-coin videos you watched today).

This file **never leaves your device**. It is not sent to us or to anyone else, and it contains no identifiers. It is deleted when you use *Settings → Reset progress* or uninstall the App.

### 2.3 Information collected automatically by third-party SDKs

When your device is online, the Google Mobile Ads SDK (AdMob) and Google's User Messaging Platform (UMP) collect the following, which is **sent directly to Google**, not to us:

| Data | Examples | Why |
|---|---|---|
| Device and advertising identifiers | Android Advertising ID (GAID) or Apple IDFA (only if you allow tracking on iOS), app-set ID, Privacy Sandbox ad IDs on Android | Serve, measure and (with consent) personalize ads; frequency capping; fraud prevention |
| Approximate location | Derived from your IP address (not GPS) | Show ads relevant to your region; comply with regional laws |
| Device and app information | Device model, operating system and version, language, screen size, app version, network type | Deliver ads that display correctly; diagnostics |
| Ad interaction data | Ads requested and shown, taps, video completions | Measure ad delivery, reward you for completed videos, prevent invalid traffic |
| Diagnostics | SDK crash and performance data | Keep the ad service working reliably |
| Consent choices | Your GDPR/US-state privacy choices (stored on your device by UMP) | Remember and respect your choices |

The Unity game engine may also collect limited technical data about the device and engine performance, as described in Unity's privacy policy (see section 3).

We do not collect precise (GPS) location, contacts, photos, microphone or camera data, health, financial or browsing data.

### 2.4 Legal bases (EEA, UK, Switzerland)

- **Consent (Art. 6(1)(a) GDPR):** personalized advertising and the storing/reading of identifiers on your device for that purpose. You are asked through Google's consent message before any personalized ads are served, and you can withdraw consent at any time (section 8).
- **Legitimate interests (Art. 6(1)(f) GDPR):** showing non-personalized (contextual) ads to fund a free game, limiting how often ads appear, and detecting fraud and abuse.
- Local game data (section 2.2) is processed on your device only, to provide the game you asked to play.

## 3. Third-party service providers

| Provider | Purpose | Their privacy information |
|---|---|---|
| **Google AdMob** (Google Mobile Ads SDK), Google LLC / Google Ireland Ltd. | Advertising: rewarded videos and occasional full-screen ads | https://policies.google.com/privacy · How Google uses data from apps: https://policies.google.com/technologies/partner-sites |
| **Google User Messaging Platform** (UMP) | Collecting and storing your privacy/consent choices | https://support.google.com/admob/answer/10113207 |
| **Ad partners selected through AdMob** (only if you consent to personalized ads in the EEA/UK) | Ad serving and measurement | Listed in the consent message; Google's list: https://support.google.com/admob/answer/9012903 |
| **Unity Technologies** (game engine) | Running the game; engine diagnostics | https://unity.com/legal/game-player-and-app-user-privacy-policy |
| **Apple App Store / Google Play** | App distribution and updates | https://www.apple.com/legal/privacy/ · https://policies.google.com/privacy |

We do not sell personal data to anyone for money. However, allowing ad partners to use advertising identifiers for personalized ads may count as "selling" or "sharing" under some US state laws; see section 8.3 to opt out.

Ads shown in the App are limited to content rated **PG or lower**.

## 4. Device permissions

The App never asks for access to your camera, microphone, photos, contacts, calendar or precise location.

**Android** (all are "normal" permissions granted at install; none shows a pop-up):

| Permission | Purpose |
|---|---|
| `INTERNET`, `ACCESS_NETWORK_STATE` | Load advertisements and the consent form; check whether a connection is available. The game itself works offline. |
| `com.google.android.gms.permission.AD_ID` | Lets the ads SDK read the Android Advertising ID (you can reset or delete it; see section 5). |
| `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Android Privacy Sandbox APIs used by the ads SDK for privacy-preserving ad selection and measurement. You can manage them in *Settings → Security & privacy → Ads privacy*. |
| `VIBRATE` | Short vibration when a ship sinks (can be turned off in the game's Settings). |
| `WAKE_LOCK`, `FOREGROUND_SERVICE` | Added by the Google Mobile Ads / Play services libraries for reliable background ad-related tasks. The game does not run in the background itself. |

**iOS:**

| Permission | Purpose |
|---|---|
| **App Tracking Transparency (ATT)** prompt | Asks whether ads may use your device's advertising identifier (IDFA) to track you across other companies' apps and websites. If you choose "Ask App Not to Track", the IDFA is not available and you will still see ads, just less personalized. |

## 5. Deleting your data

Because the App has **no accounts**, there is no account to delete and we hold no personal data on any server. You remain fully in control:

**Delete your game data inside the App**
1. Open the App and go to the island screen.
2. Tap the **gear icon** (Settings).
3. Tap **Reset progress** and confirm.
All locally stored progress and settings are erased immediately. Uninstalling the App also removes this data.

**Delete or reset advertising data**
- **Android:** *Settings → Google → Ads* (or *Settings → Security & privacy → Privacy → Ads*): **Delete advertising ID** or **Reset advertising ID**; manage *Ads privacy* (Privacy Sandbox) settings.
- **iOS:** *Settings → Privacy & Security → Tracking*: turn off tracking for the App or for all apps.
- **Change consent (EEA/UK/Switzerland and applicable US states):** in the App, *Settings → Privacy choices*.
- Data already collected by Google is handled under Google's policies; you can review and delete Google-held data at https://myaccount.google.com/data-and-privacy (if you have a Google account) and request deletion from Google at https://support.google.com/policies/troubleshooter/9009584.

**Request by email**
You can also email **emirhantunc7805@gmail.com** with the subject "Data request – Lighthouse Keeper". Because we store no personal data, we will confirm that within **30 days** and explain how to exercise your rights with Google if needed. We will never ask for passwords.

## 6. Data retention and security

- **On-device game data:** kept until you reset progress or uninstall the App.
- **Data held by us:** none. We do not operate servers or databases for this App. If you email us, we keep the correspondence only as long as needed to answer you and for no longer than **12 months**, then delete it.
- **Data processed by Google:** retained according to Google's policies. For example, Google states that it anonymizes advertising data in server logs by removing part of the IP address after 9 months and cookie information after 18 months (https://policies.google.com/technologies/retention).
- **Security:** the game file is stored in the App's private storage, which other apps cannot access under iOS and Android sandboxing. Data sent by the ads SDK is transmitted over encrypted connections (HTTPS/TLS). No method of transmission or storage is 100% secure, but we minimize risk by not collecting personal data at all.

## 7. Children's privacy

The App is a general-audience game intended for players **13 and older** and is **not directed at children under 13**. We do not knowingly collect personal data from children under 13 (COPPA) or, in the EEA/UK, from children under the age of digital consent in their country (13–16 under GDPR Art. 8) without parental consent. Ads are restricted to PG-rated content or lower.

If you are a parent or guardian and believe your child has used the App in a way that caused personal data to be collected, contact **emirhantunc7805@gmail.com**. We will help you delete the local data and request deletion of advertising data from Google.

## 8. Your rights

### 8.1 Everyone
You can play offline (no ads, no data sent), reset the App's data at any time (section 5), reset your advertising ID and limit ad tracking in your device settings.

### 8.2 EEA, UK and Switzerland (GDPR / UK GDPR / FADP)
You have the right to **access**, **rectify**, **erase**, **restrict** or **object to** the processing of your personal data, to **data portability**, and to **withdraw consent** at any time without affecting earlier processing. Withdraw or change your ad consent in *Settings → Privacy choices*. Because we do not hold personal data about you, most requests are fulfilled by Google as the ad provider; we will help you direct them. You have the right to lodge a complaint with your local data protection authority.

### 8.3 United States (CCPA/CPRA and other state laws)
In the last 12 months, the App has enabled the categories of data in section 2.3 (identifiers, internet/network activity such as ad interactions, approximate geolocation, device information) to be collected by Google for advertising. We do not sell personal information for money. Where the use of advertising identifiers for personalized ads is considered "selling" or "sharing" for cross-context behavioral advertising, you have the right to **opt out**: use *Settings → Privacy choices* in the App (where shown), turn on *Limit Ad Tracking* / delete your advertising ID (Android) or deny tracking (iOS). You also have the rights to **know/access**, **delete** and **correct**, and the right to **non-discrimination** for exercising them. Send requests to emirhantunc7805@gmail.com; we will respond within **45 days**. Authorized agents may submit requests with written permission from you.

### 8.4 Türkiye (KVKK)
Residents of Türkiye have the rights set out in Article 11 of Law No. 6698 on the Protection of Personal Data, including learning whether data is processed and requesting its deletion. Contact us at the email above.

## 9. International transfers

Google and Unity may process data in the United States and other countries. Google relies on the EU–US Data Privacy Framework and Standard Contractual Clauses for transfers from the EEA/UK/Switzerland.

## 10. Changes to this policy

If the App's data practices change (for example, if in-app purchases or analytics are added), we will update this policy and the "Last updated" date before the change takes effect, and update the store disclosures accordingly.

## 11. Contact

Emirhan Tunç — emirhantunc7805@gmail.com

---

## Appendix: App Store & Google Play disclosure cross-walk

This summary mirrors what is declared in Apple's **App Privacy** ("nutrition label") and Google Play's **Data safety** section. Data listed below is collected by the Google Mobile Ads SDK; the developer receives none of it.

| Data type | Apple category | Google Play category | Collected / Shared | Ephemeral vs. stored | Purpose | Linked to identity | Used for tracking (Apple) |
|---|---|---|---|---|---|---|---|
| Advertising ID (IDFA / GAID), app-set ID | Identifiers → Device ID | Device or other IDs | Collected and shared (with Google and its ad partners) | Stored by Google per its retention policy | Third-party advertising, analytics, fraud prevention | No | Yes (IDFA only with ATT permission) |
| Approximate location (from IP) | Location → Coarse Location | Location → Approximate location | Collected and shared | Processed per request; logs retained by Google | Third-party advertising, fraud prevention | No | No |
| Ad interactions (impressions, taps, video completions) | Usage Data → Advertising Data; Product Interaction | App activity → App interactions | Collected and shared | Stored by Google | Third-party advertising, analytics | No | Yes (with ATT permission) |
| SDK crash & performance data | Diagnostics → Crash Data, Performance Data | App info and performance → Crash logs, Diagnostics | Collected | Stored by Google | Analytics (SDK reliability) | No | No |
| Game progress & settings | Not collected (stays on device) | Not collected (stays on device) | Neither | Stored on device only | App functionality | — | — |
| Name, email, contacts, photos, precise location, financial, health | Not collected | Not collected | Neither | — | — | — | — |

**Google Play Data safety answers:** Does the app collect or share user data? *Yes.* Is all collected data encrypted in transit? *Yes.* Do you provide a way for users to request data deletion? *Yes — in-app "Reset progress" for on-device data and advertising-ID reset/deletion in device settings; see section 5.* Is the app's target audience under 13? *No.*

**Apple App Privacy answers:** Data used to track you: *Identifiers (Device ID), Usage Data (Advertising Data)*. Data not linked to you: *Coarse Location, Product Interaction, Crash Data, Performance Data*. The ATT prompt text: "Your data will be used to show you ads that are more relevant to you. The game is free thanks to ads."
