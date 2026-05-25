# Akusento — Japanese Pitch Accent Parser

[![Website](https://img.shields.io/badge/Website-akusento.com-red)](https://akusento.com)
[![Status](https://img.shields.io/badge/Status-Closed_Beta-blue)](#)

Akusento is a precision web-based Japanese pitch accent parser built for advanced learners, linguists, and language coaches. 

Instead of relying on static dictionaries that only provide isolated word pitches, Akusento analyzes full Japanese sentences and returns structured, mora-level pitch data based on contextual grammatical rules.

👉 **[Join the waitlist at akusento.com](https://akusento.com)**

## ⚙️ How It Works (Backend Engine)
The core parsing engine is currently closed-source. It operates via a highly optimized pipeline utilizing:
*   **MeCab** for morpheme parsing and tokenization.
*   **UniDic** for accurate, modern phonetic and pitch accent data.
*   **Custom Contextual Logic** to accurately map pitch shifts across conjugations and particle attachments.

## 📚 Guides & Documentation
We are building a comprehensive library on how Japanese pitch accent works and how to apply it to your studies.
*   📖 **[The Invisible Layer of Fluency: Understanding Japanese Pitch Accent](docs/understanding-pitch-accent.md)** — A complete breakdown of Heiban, Atamadaka, Nakadaka, Odaka, and the Kifuku verb classification.

## 🚀 Current Status
The web interface is currently in development. We are focusing on delivering a zero-friction, highly accurate UI for generating visual pitch accent curves over full texts. 

*   **Phase 1:** Standalone web tool (Currently capturing waitlist)
*   **Phase 2:** Closed Beta testing for edge-case dictionary tuning
*   **Phase 3:** Public launch
*   **Phase 4:** Developer API (Documentation will be published here)

## 🐛 Bug Reports & Feature Requests
Once the tool is live, this repository will serve as the public tracker for feature requests, API documentation, and public roadmap discussions. 

*(Note: Dictionary edge-cases and parsing corrections will be handled dynamically within the web app UI).*
