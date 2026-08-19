# OpenRound Support

**OpenRound** is a watch-first, account-free disc golf scorecard for iPhone and Apple Watch. Keep score hole by hole, pick from thousands of courses, and play offline — with optional iCloud sync on iPhone when you want your round history on all your devices.

This repository is for **support and privacy information only**. The app source code is not published here.

## Get help

**[Open an issue](https://github.com/thomasRhoffmann/OpenRound-support/issues)** — best for bug reports, feature requests, or how-to questions.

Please include:
- Device model and OS version (iPhone and/or Apple Watch if relevant)
- App version (Settings → About on iPhone, or Settings on Watch)
- What you expected vs. what happened
- Screenshots if helpful

## Contact

If you prefer email, contact **thoff13@gmail.com**. For faster triage, GitHub Issues are preferred so we can track fixes.

## Frequently asked questions

### Do I need an account?

No. OpenRound has no sign-in, no account, and no paywall.

### Is my round data stored in the cloud?

By default, **no**. Your rounds, scores, and player names are stored **on your devices** using Apple’s on-device storage. We do not operate servers that receive your scoring data.

On **iPhone**, you can optionally turn on **iCloud sync** in Settings. When enabled, your rounds sync privately through **your** iCloud account to your other Apple devices — not to us. iCloud sync is off by default.

### How does iPhone ↔ Apple Watch sync work?

While you play, OpenRound can mirror the active round between iPhone and Apple Watch over **WatchConnectivity** (a direct device-to-device link). This keeps scores in sync during the round.

The **Watch app is built for live scoring** on your wrist. It does not keep long-term round history or lifetime stats. Use OpenRound on **iPhone** to save every round from both devices and track progress over time.

### Can I use OpenRound without my iPhone nearby?

Yes. The Apple Watch app runs independently (`WKRunsIndependentlyOfCompanionApp`). You can start and score a full round on Watch alone. For the best experience — history, backups, sharing, and iCloud — use iPhone alongside Watch.

### How does location work?

OpenRound may ask for **location while you use the app** to sort nearby courses when you are choosing where to play. Your location is used **on device only** for sorting. It is not stored or transmitted to us.

### Where does course data come from?

The course directory is supplied by **[DiscGolfAPI](https://discgolfapi.com)** and ships bundled in the app so you can browse and play **offline**. 

### How do I back up my rounds?

On **iPhone**, go to **Settings → Export backup** to save all rounds to a portable file you own. Use **Import backup** to merge rounds from a backup file. Deleting OpenRound erases local rounds unless iCloud sync is on or you have exported a backup.

### How do I share a scorecard?

On **iPhone**, use the share options after a round (scorecard image or CSV, depending on the screen). Sharing uses the standard iOS share sheet — you choose where it goes. We do not receive copies of shared content.

### Why don’t par or distance match the course signage?

DiscGolfAPI does not provide per-hole par or distance data, so holes will always start with default values (par 3 and 0 distance). Tap **Edit hole** (Watch: More menu) or the par edit control on iPhone while you play to update par and distance; your changes stick for future rounds on that device.

### Can I add a course that isn’t in the directory?

Yes. Use **Sketch a course** on iPhone to create a custom course and layout for casual or new layouts.

## Privacy

See **[Privacy Policy](PRIVACY.md)** for how OpenRound handles information on your device.

## App Store Connect URLs

- **Support URL:** `https://thomasRhoffmann.github.io/OpenRound-support/`
- **Privacy Policy URL:** `https://thomasRhoffmann.github.io/OpenRound-support/PRIVACY.html`

## App Store

OpenRound is available on the App Store (add your listing link here once live).

---

© 2026 Thomas Hoffmann
