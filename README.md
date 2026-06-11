# akusento — Japanese Pitch Accent Parser

[![Website](https://img.shields.io/badge/Website-akusento.com-red)](https://akusento.com)

akusento is a precision web-based Japanese pitch accent parser built for advanced learners, linguists, and language coaches.

Instead of relying on static dictionaries that only provide isolated word pitches, akusento analyzes full Japanese sentences and returns structured, mora-level pitch data based on contextual grammatical rules.

## ⚙️ How It Works (Backend Engine)
The core parsing engine is currently closed-source. It operates via a highly optimized and customized pipeline utilizing:
*   **MeCab** for morpheme parsing and tokenization.
*   **UniDic** for accurate POS-tagging and handling a huge variety of Japanese text.
*   **Custom Contextual Logic** to accurately map pitch shifts across conjugations, particle attachments, compound nouns, suffixes and prefixes and much more.

## 📚 Guides & Documentation
We are building a comprehensive library on how Japanese pitch accent works and how to apply it to your studies.
*   📖 **[The Invisible Layer of Fluency: Understanding Japanese Pitch Accent](docs/understanding-pitch-accent.md)** — A complete breakdown of Heiban, Atamadaka, Nakadaka, Odaka, and the Kifuku verb classification.

## 🚀 Current Status
The web interface is currently in development. We are focusing on delivering a zero-friction, highly accurate UI for generating visual pitch accent curves over full texts. 
