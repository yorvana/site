---
layout: page
title: Privacy Policy
---

# Privacy Policy for Yorvana

**Effective date:** 18 May 2026

This policy explains what data Yorvana ("the app") handles, why, and what choices you have. It is written in plain language. If anything is unclear, contact us at the address below.

## 1. Who we are

Yorvana is an Android application for keeping a personal log of vehicle maintenance and repair history. The app is published by:

- **Igors Vinogradovs** (individual developer, acting as data controller)
- Contact: **yorvana.app@gmail.com**

## 2. What data Yorvana handles

### 2.1 Your service records ("vault data")

When you use Yorvana, you create records about your vehicles: vehicles, service entries, categories, photos and any other content you choose to add. This data is stored as plain JSON files in a folder **on your own device**, in a location you pick the first time you open the app (using Android's Storage Access Framework).

- This data **never leaves your device** through Yorvana. We do not operate any server that receives, mirrors or backs up your vault.
- We cannot read it, recover it, or restore it for you. You are in full control.
- If you back up the folder yourself (for example to a cloud drive you've configured separately), that backup is governed by *your* settings with that service, not by us.

### 2.2 App settings

Yorvana stores your in-app preferences (theme, units, opt-in flags, etc.) using Android's DataStore. These settings remain on your device and are not transmitted anywhere.

### 2.3 Crash reports (optional, opt-in only)

Crash reporting is **disabled by default**. You can turn it on in Settings → Privacy. Once you do, if the app crashes or hits an unexpected error, Yorvana sends a technical report to our error-tracking processor (see Section 5 — Third parties). A report typically contains:

- Device model and Android version
- App version
- The error type, message and stack trace
- A short list of recent in-app navigation events ("breadcrumbs"), to help us reproduce the bug
- A randomly generated installation identifier (so we can group repeated crashes from the same install — it is not tied to you personally)

Crash reports **do not include the contents of your vault** (vehicles, records, photos, notes). You can turn crash reporting off again at any time in Settings.

### 2.4 Feedback you choose to submit

If you use the in-app feedback form, the message you write — and, optionally, the email address you provide — are sent to our error-tracking processor along with technical context (app version, device model) so we can respond and act on the feedback. If you do not enter an email, your feedback is anonymous.

## 3. What we do not collect

Yorvana **does not**:

- Use third-party advertising or marketing SDKs
- Use analytics SDKs (no Firebase Analytics, Google Analytics, Amplitude, etc.)
- Track your location
- Read your contacts, calendar, microphone, camera (beyond photos you attach to a record), call logs, or other apps
- Require you to create an account or sign in
- Sell, rent or share your data with anyone for commercial purposes

## 4. Permissions Yorvana requests

| Permission | Why |
|---|---|
| `READ_EXTERNAL_STORAGE` (Android 12 and below only) | Legacy support for older Android versions so you can attach files from shared storage. Newer Android versions use the Storage Access Framework instead and do not need this permission. |
| Storage Access Framework folder grant | You explicitly pick a folder for your vault; Android then grants Yorvana access to *only that folder*. |

Yorvana does not request internet, location, contacts, camera, microphone or any other runtime permission.

## 5. Third parties

Yorvana uses **Sentry** ([sentry.io](https://sentry.io), operated by Functional Software, Inc., headquartered in the United States) as its error-tracking processor. Sentry receives crash reports and feedback submissions **only when you opt in** (Section 2.3 and 2.4). Transfer of data to the United States is covered by the EU Standard Contractual Clauses.

We do not use any other third-party services that process your personal data.

## 6. Data retention

- **Vault data on your device**: kept until you delete it. Uninstalling Yorvana does not delete the vault folder; you remove it the same way you'd remove any other folder on your device.
- **Crash reports**: stored on Sentry for up to 90 days by default, then automatically deleted.
- **Feedback submissions**: retained as long as needed to respond and act on the feedback; you can ask us to delete an earlier submission at any time (Section 9).

## 7. Children

Yorvana is not directed at children under the age of 13 (or under 16 in the European Economic Area). We do not knowingly collect data from children. If you believe a child has submitted data through the app's optional feedback form, contact us and we will delete it.

## 8. International users

Yorvana is available internationally. Vault data stays on the user's device wherever they are. Crash reports and feedback (when opted in) are processed in the United States by Sentry under the safeguards described in Section 5.

## 9. Your rights

Because Yorvana stores your vault data **on your own device**, you exercise most data-protection rights directly: you can view, edit, export or delete your records at any time within the app or by editing the JSON files in the folder you picked.

For the limited data that Sentry processes on our behalf (opt-in crash reports and feedback), you have the following rights — granted under the EU General Data Protection Regulation (GDPR) and, where applicable, the California Consumer Privacy Act (CCPA):

- **Access** — request a copy of any data we hold about you
- **Rectification** — ask us to correct inaccurate data
- **Erasure** — ask us to delete data we hold about you
- **Restriction** — ask us to stop processing your data while we investigate a request
- **Portability** — request data in a portable format
- **Object** — object to processing based on legitimate interests
- **Withdraw consent** — turn off crash reporting in Settings at any time; this stops further reports being sent
- **Lodge a complaint** — contact your local data protection authority (in the EU/EEA) or relevant regulator

To exercise any of these rights, email **yorvana.app@gmail.com**. We will respond within 30 days. To help us find your data in Sentry, please include the approximate date you submitted the feedback or experienced the crash, and your device model if known.

## 10. Changes to this policy

If we make material changes to this policy, we will update the "Effective date" at the top and, where reasonable, surface the change inside the app on the next launch. Continued use of Yorvana after a change means you accept the updated policy.

## 11. Contact

For privacy questions, data-rights requests, or anything else covered by this policy:

**yorvana.app@gmail.com**
