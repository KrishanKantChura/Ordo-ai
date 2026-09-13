# Ordo AI — Derma & CNS Care Assistant

A standalone, browser-based Ordo AI customer-care chatbot for:

- Derma & skincare
- CNS & neurology
- Orders & shipping
- Returns & refunds
- CustomerCare

## Run locally

No build tools or dependencies are required.

1. Clone/download this repository.
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

## Notes

- The chatbot currently uses a rule-based FAQ engine; it does not call an external AI API.
- FAQ content and routing are embedded directly in `index.html`.
- Google Fonts are loaded remotely by the page.
- Medical content includes a disclaimer and directs users to professional care where appropriate.
