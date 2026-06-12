# 🩺 HealthScreen AI

> Personalized health screening recommendations by age and gender, powered by Claude AI.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20App-green?style=flat-square)](https://neerajakasu.github.io/healthscreen-ai)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2B%20Vanilla%20JS-orange?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Anthropic](https://img.shields.io/badge/AI-Claude%20by%20Anthropic-blueviolet?style=flat-square)](https://www.anthropic.com)

---

## What it does

Enter your **age** and **biological sex** and instantly receive a personalised list of mandatory and recommended health screenings — based on current clinical guidelines from:

- **USPSTF** — U.S. Preventive Services Task Force
- **AHA** — American Heart Association
- **ACS** — American Cancer Society

Examples of tests it covers: blood pressure checks, cholesterol screening, colonoscopy, mammography, cervical cancer screening, diabetes screening, lung cancer screening, vision and hearing tests, and more.

---

## Screenshot

> _(Add a screenshot here after deploying — drag and drop an image into this README on GitHub)_

---

## How to use

1. Open the [live app](https://neerajakasu.github.io/healthscreen-ai)
2. Enter your age and select your biological sex
3. Click **Get my screenings**
4. Optionally add your own [Anthropic API key](https://console.anthropic.com) for higher usage limits

---

## Running locally

No build tools or dependencies needed. Just open the file in a browser:

```bash
git clone https://github.com/neerajakasu/healthscreen-ai.git
cd healthscreen-ai
open index.html
```

To call the Anthropic API from a browser, you need an API key from [console.anthropic.com](https://console.anthropic.com). New accounts receive free credits.

---

## Tech stack

| Layer | Technology |
|-------|-----------|
| Frontend | Plain HTML5 + Vanilla JavaScript |
| Styling | Pure CSS (no frameworks) |
| AI | Anthropic Claude API (`claude-sonnet-4-6`) |
| Hosting | GitHub Pages |

No Node.js. No React. No build step. One single HTML file.

---

## Project structure

```
healthscreen-ai/
└── index.html      # The entire app — HTML, CSS, and JS in one file
```

---

## API key note

This app calls the Anthropic API directly from the browser. There are two ways to use it:

- **Shared key** (default): works out of the box if the owner has pre-configured a key
- **Your own key**: click "Use your own Anthropic API key" and paste a key from [console.anthropic.com](https://console.anthropic.com) — keys are never stored or sent anywhere other than Anthropic

---

## Medical disclaimer

This tool provides general health information based on common clinical guidelines. It is **not** a substitute for professional medical advice. Always consult your doctor before making health decisions.

---

## Future improvements

- [ ] Add more gender/sex options
- [ ] Export results as PDF
- [ ] Add language selector (Spanish, Portuguese, etc.)
- [ ] Spring Boot backend version with proper API key management
- [ ] Add RAG with actual USPSTF guideline documents

---

## Author

Built by **Neeraja Kasu** — Senior Java Developer exploring AI integration.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/nkasu/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat-square&logo=github)](https://github.com/neerajakasu)

---

## License

MIT — free to use, modify, and share.
