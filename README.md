# 🩺 HealthScreen AI

> Personalized health screening recommendations by age and gender, powered by Google Gemini AI.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20App-green?style=flat-square)](https://neerajakasu.github.io/healthscreen-ai)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2B%20Vanilla%20JS-orange?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-blue?style=flat-square)](https://aistudio.google.com)

---

## What it does

Enter your **age** and **biological sex** and instantly receive a personalised list of mandatory and recommended health screenings — based on current clinical guidelines from:

- **USPSTF** — U.S. Preventive Services Task Force
- **AHA** — American Heart Association
- **ACS** — American Cancer Society

Examples of tests it covers: blood pressure checks, cholesterol screening, colonoscopy, mammography, cervical cancer screening, diabetes screening, lung cancer screening, vision and hearing tests, and more.

---

## Screenshot

> _(Add a screenshot here — drag and drop an image into this README on GitHub)_

---

## How to use

1. Open the [live app](https://neerajakasu.github.io/healthscreen-ai)
2. Enter your age and select your biological sex
3. Click **Get my screenings**
4. Results appear instantly — no login or account needed

---

## Running locally

No build tools or dependencies needed. Just open the file in a browser:

```bash
git clone https://github.com/neerajakasu/healthscreen-ai.git
cd healthscreen-ai
open index.html
```

---

## Tech stack

| Layer | Technology |
|-------|-----------|
| Frontend | Plain HTML5 + Vanilla JavaScript |
| Styling | Pure CSS (no frameworks) |
| AI | Google Gemini API (`gemini-1.5-flash`) |
| Hosting | GitHub Pages (free) |

---

## Project structure

```
healthscreen-ai/
├── index.html      # The entire app — HTML, CSS, and JS in one file
└── README.md       # This file
```

---

## Medical disclaimer

This tool provides general health information based on common clinical guidelines. It is **not** a substitute for professional medical advice. Always consult your doctor before making health decisions.

---

## Future improvements

- [ ] Add more gender options
- [ ] Export results as PDF
- [ ] Add language selector (Spanish, Portuguese, etc.)
- [ ] Spring Boot backend version with proper API key management
- [ ] Add RAG with actual USPSTF guideline documents

---

## Author

Built by **Neeraja Kasu** — Senior Java Developer exploring AI integration.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/nkasu/)
[![GitHub](https://img.shields.io/badge/GitHub-neerajakasu-black?style=flat-square&logo=github)](https://github.com/neerajakasu)

---

## License

MIT — free to use, modify, and share.
