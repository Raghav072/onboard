# ONBOARD Website Prototype — Version 4

A static front-end prototype for ONBOARD, Your All-in-Uni Companion. Includes the original social feed, student discovery and profile demos, marketplace, plus:
- Alumni discovery filters for company, programme and graduation year.
- Achievements feed with likes only (no comments or replies).
- Subscription-style premium Info Hub for DSA, Google, Amazon, graduate competitive exams, GSSoC/open source and career planning.
- Product category suggestion in the marketplace listing flow. The current browser-side classifier is a demo placeholder; connect Gemini through a secure backend for production.

Open `index.html` in a modern browser. No build tools required.

## Production notes
This prototype does not implement real authentication, verified alumni records, messaging, payment processing, persistent storage or a live Gemini integration. Do not put a Gemini API key in browser JavaScript. Store it in a server-side environment variable and call Gemini from a backend endpoint. Sample alumni data is fictional and for demonstration only.
