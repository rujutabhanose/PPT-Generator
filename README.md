
# Bonus Project – Auto-Generate a Presentation from Text

Gyaan Deck is a lightweight web app that lets anyone paste long-form text (markdown, prose, notes, reports) and instantly convert it into a styled, ready-to-present PowerPoint deck. Simply upload your own template, add optional guidance, and supply your preferred LLM API key — the app will handle the rest.

---

## Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/23f1000805/tds-bonus-project-Auto-PPT-Generator-GyaanSetu-Deck.git
cd tds-bonus-project-Auto-PPT-Generator-GyaanSetu-Deck
```

### 2. Install dependencies

```bash
# Backend (Python FastAPI + pptx libraries)
pip install -r requirements.txt

# Frontend (served as static HTML/JS/CSS)
# no build step needed
```

### 3. Run locally

```bash
uvicorn app:app --reload
```

Visit: [http://localhost:8000](http://localhost:8000)

### 4. Deploy (Railway/Render/Vercel/Heroku)

This app works out-of-the-box on cloud platforms. Just connect your repo and deploy.

---

## Usage

1. Paste your text or markdown.
2. (Optional) Add a one-line guidance like *“make it a research summary”*.
3. Paste your LLM API key (OpenAI, Anthropic, Gemini).
4. Upload a `.pptx` or `.potx` template.
5. Click **Generate** → Get your styled PowerPoint deck!

---

## License

MIT License – free to use, modify, and share.

