# Research-Paper-Writing-Assistant
# 📝 Shodh Likhawat Fatafat!

> **Shodh** (शोध) — Research &nbsp;|&nbsp; **Likhawat** (लिखावट) — Writing &nbsp;|&nbsp; **Fatafat** (फटाफट) — Instantly

An AI-powered research writing assistant that helps students and researchers turn their understanding of academic papers into properly cited, grammatically correct academic prose — instantly.

---

## ✨ What It Does

You bring the idea. The tool writes it like a researcher.

Paste what you understood from a paper, drop in the citation, choose how you want it written — and get publication-ready academic sentences in seconds.

---

## 🚀 Features

- **Paraphrase & Cite** — Rewrites your understanding in formal academic English with a proper in-text citation and 2–3 sentence variants to choose from
- **Direct Quote** — Formats the idea as a direct quotation with signal phrase variations and correct citation syntax
- **Any citation format** — Works with APA, MLA, Chicago, or any standard format
- **Example chips** — Pre-loaded demos so you can try it instantly
- **Streaming output** — Results appear word-by-word in real time
- **One-click copy** — Copy generated text to clipboard instantly
- **Secure API key storage** — Your Gemini API key is entered once and stored locally in the browser; never sent to any third-party server

---

## 🔑 API Key Setup

Shodh Likhawat Fatafat uses the **Google Gemini API** for natural language generation.

1. Get your free API key from [Google AI Studio](https://aistudio.google.com/app/apikey)
2. On first launch, you'll be prompted to enter your API key
3. The key is saved to `localStorage` — you won't need to enter it again
4. To reset or change the key, clear your browser's local storage for this page

> **Privacy note:** Your API key is stored only in your own browser and is used exclusively to call the Gemini API directly. It is never logged or transmitted elsewhere.

---

## 🖥️ How to Use

1. **Enter your understanding** — Write in plain language what you understood from the paper or what point you want to make
2. **Enter the citation** — Paste the full citation of the paper in any standard format
3. **Choose your mode:**
   - *Paraphrase & cite* — for rewording an idea academically
   - *Direct quote* — for using the author's exact words
4. **Click Generate** — Your academic sentence(s) will stream in within seconds
5. **Copy & paste** into your paper

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript (single file) |
| AI Engine | Google Gemini API |
| API Key Storage | Browser `localStorage` |
| Fonts | Playfair Display + DM Sans (Google Fonts) |
| Hosting | Static file — open directly in browser or deploy anywhere |

---

## 📁 Project Structure

```
shodh-likhawat-fatafat/
├── index.html        # Entire app — self-contained single file
└── README.md         # This file
```

No build tools. No dependencies. No backend. Just open `index.html` in a browser.

---

## 🧪 Example

**You type:**
> The paper argues that attention mechanisms are better than recurrent connections at capturing long-range dependencies in text.

**Citation:**
> Vaswani et al. (2017). Attention is all you need. NeurIPS, 30.

**Generated (Paraphrase mode):**
> Vaswani et al. (2017) contend that attention mechanisms are more effective than recurrent neural networks for modeling long-range dependencies in textual data.

---

## 🔮 Planned Features

- [ ] Citation style selector (APA / MLA / Chicago toggle)
- [ ] Session history — save and revisit past generations
- [ ] PDF upload — extract text directly from a paper
- [ ] Export to `.docx` — download all citations as a Word document
- [ ] Literature review mode — chain multiple citations into paragraphs
- [ ] Full reference list generator

---

## 🤝 Contributing

Pull requests are welcome! If you have ideas for new writing modes, citation formats, or UI improvements, feel free to open an issue or submit a PR.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Built with ❤️ for researchers, by researchers. शोध लिखावट फटाफट!*
