# Privacy Policy for Pocket Puzzles

**Last updated:** 20 September 2026

This policy explains what Pocket Puzzles ("the app", "we") does with your
information. It applies to the Android app published under the package name
`io.github.bogdanovi.pocket_puzzles`.

## Summary

Pocket Puzzles is a collection of offline puzzle games. There is no account, no
sign-in and no server of ours. Your game progress, settings and reminder choice
stay **on your device**.

The exceptions are advertising and the optional "No Ads" purchase: the app shows
ads through Google AdMob, and confirms a purchase through Google Play and
RevenueCat. What those services collect is described in section 4.

## 1. Who is responsible

This app is developed and published by an individual developer.

Contact: ibogdanovdec@gmail.com

## 2. What the app does with your information

- The games run entirely on your device. Puzzle levels are bundled inside the
  app; nothing is downloaded to play them.
- The app contains no server, no account system and no way to upload your
  progress or anything else to us.
- We do not ask for your name, email address, location, contacts, photos or any
  other personal information.

## 3. Data stored on your device

The app saves a small set of preferences locally (via Android SharedPreferences).
This never leaves the device and is removed when you uninstall the app:

- which levels you have completed and how many levels you have unlocked in each
  game
- your chosen language and light/dark theme
- which game tutorials you have already seen
- whether the daily reminder is switched on
- whether "No Ads" was last confirmed as owned (so ads stay off when you open
  the app without a connection)

We have no access to any of it.

## 4. Advertising (Google AdMob)

The app displays a banner ad and optional rewarded video ads (which you choose
to watch to unlock more levels) via **Google AdMob**. To serve ads, the Google
Mobile Ads SDK collects and processes data independently of us, including:

- your device's **advertising ID** (a resettable identifier)
- device and app information (device model, operating system version, app
  version, coarse language/region settings)
- your **IP address**, from which approximate location may be derived
- ad interaction data (impressions, clicks, rewarded-ad completions)
- ad attribution and interest signals via the Android Privacy Sandbox
  (Topics and Attribution APIs)

This processing is carried out by Google as an independent controller/processor
under its own terms. See:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses information from partner apps:
  https://policies.google.com/technologies/partner-sites

We do not receive your advertising ID or your personal data from Google; we only
see aggregate, non-identifying earnings and performance reports.

Video ads only play when you choose to watch one; the app has no full-screen ads
that appear on their own.

### Consent in the EEA, UK and Switzerland

If you are in the European Economic Area, the United Kingdom or Switzerland, the
app asks for your consent before serving personalised ads, using Google's
User Messaging Platform (UMP), the first time you open it. You may withdraw or
change your consent at any time from the app's settings, under "Ad privacy
settings". If you decline personalised ads, you may still see ads, but
non-personalised or limited ones, as Google's rules allow.

No ads are requested at all until this consent step has completed.

### "No Ads" purchase

"No Ads" is a one-time purchase that removes the banner, removes the videos and
opens every level. Purchases are processed by **Google Play**, and your
entitlement is managed on our behalf by **RevenueCat**, which receives a
pseudonymous app user identifier and your purchase receipt in order to confirm
it. RevenueCat does not receive your name, email address or anything from your
device beyond what is needed to confirm the purchase. See
https://www.revenuecat.com/privacy/ for their policy.

We never see or handle your payment details; those stay with Google Play. If you
reinstall the app or move to a new phone, "Restore purchase" in the app brings
the purchase back through your Google account.

## 5. Notifications

The app can remind you to come back to a puzzle. The reminder is a **local
notification** scheduled by the app on your device: about a day after you last
opened the app, and daily after that for up to a week, only if you do not open
it in between. It uses no push service, no server and no identifier, and
nothing about it is sent anywhere.

On first launch the app asks for permission to show notifications. You can
decline, and you can switch the reminder on or off at any time in the app's
settings.

## 6. Permissions and why they are needed

| Permission | Why |
| --- | --- |
| `POST_NOTIFICATIONS` | To show the daily reminder, only if you allow it. |
| `RECEIVE_BOOT_COMPLETED` | So a scheduled reminder survives a phone restart. The app does not start itself on boot or run in the background. |
| `VIBRATE` | Declared by the notification library the app uses. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Added by the Google Mobile Ads SDK to load ads and by RevenueCat to confirm your purchase. Outside those two, the app makes no network requests — the games work fully offline. |
| `FOREGROUND_SERVICE`, `WAKE_LOCK` | Declared by background-task code inside the ads SDK. The app runs no service of its own. |
| `com.google.android.gms.permission.AD_ID`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS` | Added by the Google Mobile Ads SDK for advertising identification, ad attribution and Android Privacy Sandbox topics. Used by Google for advertising as described in section 4. |
| `com.android.vending.BILLING` | Added by Google Play Billing so the one-time "No Ads" purchase can be made. |

## 7. Analytics and crash reporting

The app contains **no analytics SDK and no crash reporting SDK**. We do not track
your usage.

If you install the app from Google Play, Google may collect its own standard
crash and usage data as part of the Play platform, independently of us. See
Google Play's privacy terms.

## 8. Children

The app is not directed at children under 13 and we do not knowingly collect
personal data from them.

## 9. Data retention and your rights

Because we do not collect or receive personal data, we hold nothing to retain,
export, or delete. To remove everything the app has stored:

- uninstall the app — all local progress and preferences are deleted with it.

Regarding advertising data held by Google, you can:

- reset or delete your advertising ID in **Android Settings → Privacy → Ads**
- change your consent choices in the app (EEA/UK/Switzerland)
- exercise your GDPR rights (access, rectification, erasure, objection) directly
  with Google via https://policies.google.com/privacy

## 10. Changes to this policy

If this policy changes, the updated version will be published at this same URL
with a new "Last updated" date. Material changes affecting how data is handled
will also be noted in the app's Play Store release notes.

## 11. Contact

Questions about this policy: ibogdanovdec@gmail.com
