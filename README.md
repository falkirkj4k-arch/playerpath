# PlayerPath MVP prototype

## Run it
1. Unzip the folder.
2. Open `index.html` in Chrome, Safari, Edge or Firefox.
3. The demo opens with sample players and records. No installation or account is required.

## What works
- Add players and maintain a player directory
- Record dated assessments with a 1–5 development indicator, strengths and next focus
- Create and complete individual development targets
- View player histories
- Generate a parent-friendly report and print/save it as PDF
- Goalkeeper assessment framework and specialist assessment flow
- Export club data as JSON
- Data persists in the browser using local storage

## Important limitations
This is a functional browser prototype, not yet a production multi-club SaaS application. It has no real login, cloud database, parent accounts, permissions, backups or secure multi-user syncing. Data stays in the browser/device where it is entered. Do not enter real children's personal information into this prototype.

## Next production build
A production version should add:
- Supabase authentication and database with club-level tenant isolation
- Coach, club-admin and parent roles
- Secure child-data handling, guardian workflows and retention/deletion controls
- Cloud backups, audit history and access permissions
- Annual club subscriptions and onboarding
- Proper PDF generation and optional parent sharing

The product should receive a UK GDPR / Children's Code privacy review before real children's data is collected.
