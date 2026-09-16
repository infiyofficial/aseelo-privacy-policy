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
Aseelo does **not** collect analytics, crash reports, advertising identifiers, or device identifiers. We do not use any third-party analytics SDKs or advertising SDKs.

### 1.3 In-App Purchases
Aseelo offers optional premium subscriptions through **Google Play Billing**. When you make a purchase:
- Google Play processes the transaction and shares with us only a **purchase token** and **subscription status** (active/inactive).
- We do **not** receive your name, email, payment method, or billing address.
- We do **not** store your purchase information on any server — subscription status is verified in real time via Google Play's Billing API.

Google's handling of your data is governed by Google's Privacy Policy:  
https://policies.google.com/privacy

---

## 2. How We Use Information

Because Aseelo operates locally on your device, we do not use your information for any purpose other than:

- Scheduling and triggering your alarms at the correct times
- Playing your chosen ringtone
- Managing your premium subscription status via Google Play
- Remembering your app preferences

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

You can revoke any of these permissions at any time in your device's Settings app.

---

## 4. Data Storage and Security

All alarm data is stored locally on your device using Android's `SharedPreferences` mechanism. This data is:
- Sandboxed to the Aseelo app (other apps cannot access it)
- Removed automatically when you uninstall the App
- Never uploaded to any server

We do not operate any backend servers that store user data.

---

## 5. Children's Privacy

Aseelo is not directed to children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us so we can take appropriate action.

---

## 6. Your Rights

Since Aseelo does not collect personal data on any server, there is no data for us to delete, export, or modify on your behalf. To remove all Aseelo data:
- **Uninstall the App** — this removes all locally stored settings and alarms.

For subscription-related data, please manage your subscriptions directly through the Google Play Store:
- Open Google Play Store → Menu → Subscriptions
- Select Aseelo Premium → Cancel or manage

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last updated" date. Continued use of the App after changes constitutes acceptance of the new policy.

---

## 8. Contact Us

If you have any questions about this Privacy Policy, please contact us:

**Email:** official.infiy@gmail.com  
**Developer:** Infiy  
**App:** Aseelo (com.infiy.aseelo)

---

*This privacy policy applies to the Aseelo Android application distributed via Google Play Store.*
