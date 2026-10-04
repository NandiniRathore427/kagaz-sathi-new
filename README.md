# Kagaz Saathi (कागज़ साथी)

Take a photo of any official paper (bill, notice, letter) and get a plain-language explanation in **English or Hindi**:
what it is, how much, the deadline, and what to do next.

Built for Hacktoberfest 2026 Hack Day.

## Features
- Photo in, simple explanation out (no sign-up, no API key for the user)
- English / हिंदी switch, with read-aloud
- Checklist of next steps, deadline countdown, calendar reminder
- Dark mode

## Deploy
1. Get a free key at https://aistudio.google.com (Get API key).
2. Push this repo to GitHub.
3. On https://vercel.com: Add New > Project > import the repo.
4. Add the environment variable `GEMINI_API_KEY` = your key, then Deploy.

## Structure
- `index.html`, `style.css`, `script.js`, `lang.js` : frontend
- `api/explain.js` : serverless backend (keeps the API key secret)

## License
MIT
