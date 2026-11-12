# EVOLVE — Personal Growth

A mobile-first, local-first personal growth app focused on BODY and MIND. It lives in `/` so the existing Progress Space app at the repository root remains untouched.

## Included
- Today dashboard with up to three daily focus actions
- BODY: home strength workouts A/B, a 15-minute low-energy option, and walking/cycling logs
- MIND: learning-session logging with topic and next-step notes
- Progress view with weekly summaries, activity totals, and reflection
- Three strength sessions as a flexible baseline; no quotas for learning or walking
- Welcome-back restart flow after a break; no streak penalties or overdue tasks
- JSON backup and restore
- PWA manifest and service worker for Add to Home Screen and basic offline support

## Data and privacy
Activity data is stored in browser localStorage on this device and browser origin. There is no account, server database, or automatic sync. This app's data is separate from the existing Progress Space app. Export a JSON backup before clearing browser data or changing devices.

## Deploy and test
When the repository is served as a static site from its root, open `/`. Test on iPhone Safari over HTTPS, including Add to Home Screen, persistence, backup/restore, and offline behaviour before relying on it as your only record.
