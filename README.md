# CareerKit

**An offline-first career companion for Filipino students and job seekers, from OJT to employment.**

Store your career once, track every requirement, and apply with confidence, from your first OJT to your first job.

Built with React Native (Expo SDK 58), TypeScript, Expo Router and SQLite. Everything stays on the device: no account, no server, no internet needed.

## Features

- **Career Vault + Document Locker**: profile, education, experience, projects, skills and certifications, with attached PDFs and images.
- **Resume Builder**: pick entries per job and export an ATS-friendly or modern PDF resume. Saved versions are kept.
- **Requirements Tracker**: Philippine pre-employment documents (NBI, Police, Barangay clearance and more), smart templates, expiry status and reminders.
- **Application Tracker**: status pipeline from applied to offer, the linked resume version, and interview reminders.
- **OJT Logger**: daily time records, hours progress, an OJT requirements checklist and a DTR PDF.
- **Dashboard**: a Career Readiness Score with suggestions on what to do next.
- **App Lock**: PIN with biometric unlock.

## Run it

```bash
npm install
npx expo start
```

Scan the QR code with **Expo Go** (Android or iOS). For the demo, use **Settings → Load demo data**.

## Docs

- [CLAUDE.md](CLAUDE.md): the project spec (SRS), architecture and build order.
- [TESTING.md](TESTING.md): the device test checklist and bug log.
