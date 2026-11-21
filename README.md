# TutorMatch — Student & Teacher Learning Community

TutorMatch is a browser-first learning platform prototype with three areas:

1. **Teacher discovery:** search sample educator profiles, filter by subject and teaching style, save educators and submit academic study requests.
2. **Student Commons:** create discussions, reply to classmates, filter by topic and mark useful posts.
3. **Learning dashboard:** create study goals, plan sessions, review local activity, open curated learning resources, switch dark mode and export a JSON backup.

## Run locally

- Open `index.html` in a modern browser, or use VS Code Live Server.
- No build tools or package installation are required.

## Prototype features

- Responsive teacher discovery and filters.
- Save educator shortlist.
- Study request form.
- Student discussion feed with topic categories, replies and helpful counts.
- Personal study goals with completion checkboxes.
- Date/time study planner.
- Curated external learning resource links.
- Local activity snapshot.
- Dark mode toggle.
- Export local data as JSON and clear local data.
- Browser `localStorage` persistence.

## Important limitations

This is still a **front-end prototype**. Educator profiles are fictional examples. Study requests, saved educators, goals, plans and community posts are stored only in the current browser and are **not shared between users**. The study planner is a personal reminder list; it does not send calendar invitations or notifications. There is no server, authentication, real teacher verification, live messaging, cross-device synchronization, or production moderation system.

Do not enter sensitive personal information in this demo. Before a real campus launch, add a secure backend and database, verified student/teacher accounts, role-based permissions, institution-approved teacher onboarding, reporting and moderation workflows, privacy controls, rate limits, and safeguarding procedures. Security and accessibility testing are also required.

## Suggested production milestones

1. Backend API and database.
2. Verified student and teacher registration with role-based access.
3. Shared teacher profiles, availability and real session booking.
4. Shared discussion feed, moderation and reporting.
5. Notifications, calendar integration and secure messaging.
6. Deployment, automated tests, accessibility and security review.

---
Built as a learning project by **adfilm29**.
