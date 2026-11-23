# Consent Tutor — Interactive Narrative Simulator & Telegram Mini App

An interactive scenario simulator built for **youth** and **parents** to explore bodily autonomy, boundary setting, subtle intra-familial grooming dynamics, somatic warning cues, and safe intervention steps—designed to run in a browser or inside **Telegram** as a Mini App.

## Core Features
- **Dual Library Storage:** Combines read-only base scenarios with user-managed personal scenarios saved locally (`localStorage`).
- **JSON, CSV & Google Sheets Support:** Import and export `.json` and `.csv` scenario files, download templates, or load public Google Sheets CSV links.
- **Clinical & Survivor Review Lens:** Displays review notes across four perspectives—child trauma/forensic interviewing, grooming and family dynamics, lived-experience survivor advocacy, and child protection/helpline response.
- **Somatic Cues & Consent Principles:** Pairs narrative branches with physical nervous-system signals (tight chest, shallow breath, freezing) and explicit boundary/protection principles.
- **Youth & Parent Tracks:** Includes scenarios on boundary dismissal, secret-keeping and grooming progression, and how parents can notice subtle shifts, talk safely without leading questions, and connect with support.
- **AI Scenario Drafting & Quick Exit:** Supports generating additional board-audited scenarios via API and includes a one-click / `Esc`-key **Quick Exit** screen that closes the Telegram Mini App or switches to a neutral decoy page.

## Running Locally & Deploying to Telegram
1. **Local preview:** Serve the HTML file over HTTP (`python3 -m http.server 8000`) and open `http://localhost:8000/Consent_Tutor_Simulator.html` rather than opening a raw `file://` path.
2. **HTTPS hosting:** Deploy over `https://` (for example via GitHub Pages, Vercel, or Cloudflare Pages).
3. **Telegram Mini App:** Attach the `https://` URL to a bot in `@BotFather` using `/newapp`, `/setmenubutton`, or **Configure Mini App**.
