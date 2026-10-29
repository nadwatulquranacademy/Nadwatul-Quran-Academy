Nadwatul Quran Academy — functional prototype v2

Files:
- index.html: homepage, courses, admission form, quiz area and demo admin panel
- nqa-logo.jpg: supplied academy logo

What works in this prototype:
- Admission form stores demo entries in the same browser's localStorage.
- Admin demo login: username admin / password NqaDemo2026!
- Admin can create demo student credentials, add quiz questions, set start/end time.
- Quiz section is hidden outside the configured quiz window and requires a demo student login.
- Quiz score is calculated in the browser.

IMPORTANT LIMITATIONS:
- This is a local prototype, not a production-ready public website.
- localStorage is not a secure database, credentials are not securely hashed, and data is only on the current browser/device.
- Do not use the demo admin password or this setup for real student information.
- For a real public website, connect a secure backend/database/auth system and server-side time-window enforcement, and deploy to a hosting service.
- No real admission submission is sent to the academy yet.
