# Ordo AI — Derma & CNS Care Assistant

A standalone, browser-based Ordo AI customer-care chatbot for:

- Derma & skincare
- CNS & neurology
- Orders & shipping
- Returns & refunds
- Customer Care

## Run locally

No build tools or dependencies are required.

1. Clone or download this repository.
2. Open `index.html` in a browser.

The chatbot is implemented as a self-contained HTML/CSS/JavaScript application.

## Deploy with GitHub Pages

1. Push this project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save.

GitHub Pages will serve `index.html` as the website entry point.

## Project structure

```text
ordo-ai-github/
├── index.html
└── README.md
```

## Product Manager summary

### Objective
Improve the customer support experience by making the chatbot answer questions instantly and accurately without noticeable waiting time.

### User value
- Faster resolution for common questions about derma, CNS, shipping, and returns
- Reduced friction for first-time users who ask natural-language questions
- Better support coverage across product categories without requiring a live agent for every query

### What was implemented
- Added an automatic intent-analysis layer that scores all supported FAQ topics against the user's query
- Prioritized the best-matching response in real time
- Removed unnecessary response delay so answers appear immediately after the user submits a question
- Kept the bot lightweight, fast, and fully browser-based with no external dependency required

### Why this matters
This makes the chatbot feel responsive and reliable in real customer conversations, which improves trust, lowers abandonment, and supports a stronger self-serve support journey for Ordomed users.

## Notes

- The chatbot currently uses a rule-based FAQ engine; it does not call an external AI API.
- FAQ content and routing are embedded directly in `index.html`.
- Google Fonts are loaded remotely by the page.
- Medical content includes a disclaimer and directs users to professional care where appropriate.
