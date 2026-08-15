# Privacy Policy — Docs Studio

**Last updated: 11 August 2026**

Docs Studio ("the app") is an offline document viewer and editor for iOS. This policy explains what the app does and does not do with your information.

## Summary

The app collects no personal data. It has no user accounts, no analytics, no advertising, and no tracking. It does not contain networking code and does not send your documents or any other information to us or to any third party.

## Data we collect

**None.** We operate no servers and receive nothing from the app. There is no sign-up, no login, and no identifier tied to you.

## Data the app stores on your device

Everything the app works with stays in the app's own storage on your device (or in iCloud Drive, if you choose to store files there through the system Files app):

- **Your documents.** Files you create, import, or open (PDF, Word, Excel, PowerPoint, ePub, text, Markdown, CSV, and the app's own `.mofficelock` locked files) are copied into the app's Documents folder and stored there. Files opened from other apps are imported, not edited in place.
- **Settings and recent-file references.** Preferences and bookmarks to files you have opened are saved in the app's local preferences store.
- **Passwords for locked documents.** Passwords you set on a locked document are never stored. They are used to derive an encryption key with Apple's CryptoKit, on device, at the moment you lock or unlock the file. If you forget a document password, the document cannot be recovered by us or by anyone.

You control this data. Deleting the app removes everything it stored on the device; individual files can be deleted from the app's file browser or from the Files app.

## Device permissions

- **Camera** — requested only when you use the document scanner, to capture pages into a PDF. Images are processed on device and saved as a document in the app. Nothing is uploaded. Denying access disables scanning only.
- **Files / document picker** — used when you import or export a document you select. The app accesses only the files you pick.

The app does not request location, contacts, photos library, microphone, notifications, or health data.

## On-device processing

Some features analyse document content locally on your device and send nothing off it:

- **Text recognition (OCR)** on scanned pages, using Apple's Vision framework.
- **Summaries and writing assistance**, using Apple's on-device Foundation Models (Apple Intelligence). Availability depends on your device and iOS version.
- **Read aloud**, using Apple's built-in speech synthesis.

These are Apple system features running on your hardware. Their behaviour is governed by Apple's own privacy policy and iOS settings.

## Sharing and third parties

We share nothing, because we receive nothing. The app bundles no third-party SDKs, analytics libraries, or advertising networks. If you use the iOS share sheet to send a document to another app or service, that transfer is initiated by you, and the receiving app's privacy policy then applies.

## Tracking

The app does not track you across apps or websites, does not use the Advertising Identifier, and contacts no tracking domains. This is declared in the app's privacy manifest (`NSPrivacyTracking: false`, no collected data types).

## Children

The app is safe for all ages: it collects no data from anyone, including children under 13.

## Your rights

Since we hold no data about you, there is nothing for us to access, correct, export, or delete on your behalf. Under GDPR, CCPA, and similar laws, requests of this kind are satisfied by your own control over the files on your device.

## Security

Locked documents are encrypted on device using Apple's CryptoKit. Everything else relies on iOS file protection and device encryption. Keep your device passcode enabled.

## Changes to this policy

If the app ever gains a feature that transmits data, this policy will be updated before that feature ships, and the "Last updated" date above will change.

## Contact

Questions about this policy: **ktnapps@gmail.com**
