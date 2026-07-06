# akusento — Japanese Pitch Accent Parser

[![Website](https://img.shields.io/badge/Website-akusento.com-red)](https://akusento.com)
[![Status](https://img.shields.io/badge/Status-Research%20Preview-orange)](https://akusento.com/about/)

akusento is a precision web-based Japanese pitch accent parser built for advanced learners, linguists, and language coaches.

Instead of relying on static dictionaries that only provide isolated word pitches, akusento analyzes full Japanese sentences and returns structured, mora-level pitch data based on contextual grammatical rules — the same way pitch actually behaves when Japanese is spoken.

---

## 🌐 Explore the site

The project has grown from a single parser demo into a small ecosystem of tools for studying and applying pitch accent:

| Route | What it does |
|---|---|
| **[/guide/](https://akusento.com/guide/)** | A comprehensive breakdown of how Japanese pitch accent actually works — heiban, atamadaka, nakadaka, odaka, the heiban/kifuku verb shortcut, compound noun rules, and more. |
| **[/parser/](https://akusento.com/parser/)** | Live preview of the parser engine on real sentences, rendering mora-level pitch curves, furigana, and devoicing marks. |
| **[/train/](https://akusento.com/train/)** | An interactive drill: mark the accented morae in real Japanese sentences (via Tatoeba), then compare your answer against the parser. Easy / Medium / Hard / Mixed difficulty pools. |
| **[/search/](https://akusento.com/search/)** | A pitch accent dictionary covering ~200,000 unique Japanese words, including wildcard and regex-style pattern search. |
| **[/library/](https://akusento.com/library/)** | A growing collection of canonical Japanese literary works — currently 夏目漱石『坊っちゃん』— rendered in full with mora-level pitch accent, furigana, and devoicing marks, chapter by chapter. |
| **[/about/](https://akusento.com/about/)** | Details on how the parser is benchmarked, including accuracy figures measured against real literary prose and professional audiobook narration. |

The site is fully localized into English, German, Spanish, Indonesian, Japanese, Korean, and Simplified Chinese.

---

## ⚙️ How it works (backend engine)

The core parsing engine is currently closed-source while it's under active development. It operates via a highly optimized and customized pipeline utilizing:

- **MeCab** for morpheme parsing and tokenization.
- **UniDic** for accurate POS-tagging across a huge variety of Japanese text, from contemporary prose to pre-war literary Japanese.
- **Custom contextual logic** to accurately map pitch shifts across conjugations, particle attachments, compound nouns, suffixes, prefixes, and much more.

The parser is continuously benchmarked against real literary prose rather than isolated dictionary entries — see [/about/](https://akusento.com/about/) for the current accuracy figures and methodology.

---

## 📚 Guides & documentation

We're building a comprehensive library on how Japanese pitch accent works and how to apply it to your studies.

- 📖 **[The Invisible Layer of Fluency: Understanding Japanese Pitch Accent](docs/understanding-pitch-accent.md)** — a complete breakdown of Heiban, Atamadaka, Nakadaka, Odaka, and the Heiban/Kifuku verb classification shortcut, plus why static dictionaries fall short once words are used in context.
- The full interactive guide, with diagrams and worked examples, is live at [akusento.com/guide/](https://akusento.com/guide/).

---

## 🚀 Current status

akusento is currently a **research preview** in active development. The public site includes the full guide, training tool, dictionary search, and literary library, all built on cached parser output — the live parser backend itself remains private during testing.

Development is focused on improving accent-rule coverage, parser accuracy, evaluation methods, and explainable output.

If you're learning Japanese, teaching pitch accent, working with Japanese-language tools, or interested in the technical side of the parser, feedback during this closed preview is especially welcome.

📬 Interested in testing akusento or sharing feedback? Contact **hello@akusento.com**
