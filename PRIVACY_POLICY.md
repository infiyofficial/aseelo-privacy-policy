# Privacy Policy for Aseelo

**Last updated: September 16, 2026**

This Privacy Policy describes how Aseelo ("we", "us", or "our") collects, uses, and shares information when you use our mobile application **Aseelo** (the "App"). By using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

### 1.1 Information You Provide

Aseelo is designed to work primarily on your device. We do **not** require you to create an account, and we do **not** collect personal information such as your name, email address, or phone number.

The following data is stored **locally on your device only** and is never transmitted to us:

- Alarm configurations (time, label, repeat days)
- Required tap counts and gap settings
- Your selected ringtone URI and name
- Vibration preferences
- Theme preference (light/dark mode)

### 1.2 Information Collected Automatically

Aseelo uses **Google Analytics for Firebase** to understand how users interact with the App. This service automatically collects:

- **App-instance ID** — a randomly generated, anonymous identifier
- **Android Advertising ID** — used for analytics attribution
- **App interactions** — screens viewed, features used, events fired
- **Device information** — device model, OS version, country
- **Session data** — app opens, session duration

This data is collected for the purpose of improving the App's features and user experience. The data is anonymous and cannot be used to personally identify you.

Google's handling of this data is governed by Google's Privacy Policy:  
https://policies.google.com/privacy

You can opt out of Analytics collection at any time by disabling usage & diagnostics in your device's Settings.

### 1.3 In-App Purchases

Aseelo offers optional premium subscriptions through **Google Play Billing**. When you make a purchase:

- Google Play processes the transaction and shares with us only a **purchase token** and **subscription status** (active/inactive).
- We do **not** receive your name, email, payment method, or billing address.
- We do **not** store your purchase information on any server — subscription status is verified in real time via Google Play's Billing API.

Google's handling of your data is governed by Google's Privacy Policy:  
https://policies.google.com/privacy

---

## 2. How We Use Information

Aseelo uses the information described above for the following purposes:

- **Alarm functionality** — to schedule and trigger your alarms at the correct times, play your chosen ringtone, and remember your app preferences.
- **Analytics** — to understand how users interact with the App, identify popular features, and improve the overall user experience.
- **Subscription management** — to verify your premium subscription status via Google Play.

We do **not** sell, rent, or share any personal information with third parties.

---

## 3. Permissions We Request

Aseelo requests the following Android permissions to function properly:

| Permission | Purpose |
|-----------|---------|
| `SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` | Schedule alarms at exact times |
| `VIBRATE` | Vibrate the device when an alarm fires |
| `FOREGROUND_SERVICE` | Keep the alarm sound and overlay running reliably |
| `SYSTEM_ALERT_WINDOW` | Display the alarm overlay on top of other apps and the lock screen |
| `RECEIVE_BOOT_COMPLETED` | Restore your alarms after the device restarts |
| `WAKE_LOCK` | Wake the device when an alarm fires |
| `READ_MEDIA_AUDIO` / `READ_EXTERNAL_STORAGE` | Let you choose a custom ringtone from your device |
| `com.android.vending.BILLING` | Process premium subscription purchases via Google Play |
| `INTERNET` | Required for Firebase Analytics to send anonymous usage data |

You can revoke any of these permissions at any time in your device's Settings app.

---

## 4. Data Storage and Security

All alarm data is stored locally on your device using Android's `SharedPreferences` mechanism. This data is:

- Sandboxed to the Aseelo app (other apps cannot access it)
- Removed automatically when you uninstall the App
- Never uploaded to any server

Analytics data is collected and processed by Google's Firebase platform under their security standards. We do not operate any backend servers that store user data.

---

## 5. Third-Party Services

Aseelo uses the following third-party services, each with their own privacy policies:

| Service | Purpose | Privacy Policy |
|---------|---------|---------------|
| **Google Analytics for Firebase** | Anonymous usage analytics | https://firebase.google.com/support/privacy |
| **Google Play Billing** | Subscription payments | https://policies.google.com/privacy |
| **Google Play Services** | Core Android functionality | https://policies.google.com/privacy |

We encourage you to review their respective privacy policies to understand how they handle your data.

---

## 6. Children's Privacy

Aseelo is not directed to children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us so we can take appropriate action.

---

## 7. Your Rights

Since Aseelo does not collect personal data on any server, there is no data for us to delete, export, or modify on your behalf. To remove all Aseelo data:

- **Uninstall the App** — this removes all locally stored settings and alarms.

To limit analytics collection:

- **Opt out via device settings** — disable "Usage & Diagnostics" or "Ads personalization" in your Android Settings app.
- **Reset your Advertising ID** — Settings → Privacy → Ads → Reset advertising ID.

For subscription-related data, please manage your subscriptions directly through the Google Play Store:

- Open Google Play Store → Menu → Subscriptions
- Select Aseelo Premium → Cancel or manage

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last updated" date. Continued use of the App after changes constitutes acceptance of the new policy.

---

## 9. Contact Us

If you have any questions about this Privacy Policy, please contact us:

**Email:** official.infiy@gmail.com  
**Developer:** Infiy  
**App:** Aseelo (com.infiy.aseelo)

---

*This privacy policy applies to the Aseelo Android application distributed via Google Play Store.*
