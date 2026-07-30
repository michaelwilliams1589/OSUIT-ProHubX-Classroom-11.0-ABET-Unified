# Firebase Rules Update Required for 10.3

Publish the included `firebase-rules.json` in the same Realtime Database used by `firebase-config.js`.

These rules explicitly allow the workspace owner, admin, chair, and assistant dean to approve instructors, remove profiles and roles, block accounts, and delete permitted personal data. They do not grant broad access to `/courseMembers`.
