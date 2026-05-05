# 👗 StyleSync AI
### Body-Intelligent Personal Styling Assistant

> An AI-powered app that analyzes your body type, proportions, facial structure, and posture — then recommends the perfect outfits, hairstyles, and movement style to help you look and feel your best.

---

## 🌏 Overview

StyleSync AI is a multimodal AI application targeting the **Southeast Asian market** — a region of 680 million people with a fast-growing fashion-conscious middle class and limited access to professional personal stylists.

We use **Xiaomi MiMo-V2.5**'s native vision-language capabilities to analyze user photos and deliver hyper-personalized recommendations across fashion, grooming, and personal presence.

---

## ✨ Core Features

### 1. 🧍 Body Type & Proportion Analysis
- Detects body type: **Ectomorph** (slim), **Mesomorph** (athletic), **Endomorph** (fuller)
- Analyzes **torso-to-leg ratio** (long torso / long legs)
- Recommends clothing **cuts, silhouettes, and fits** that visually balance and elevate the user's natural proportions

### 2. 👔 Smart Outfit Recommendations
Based on body analysis + user preference, the app generates ranked outfit suggestions for:

| Style | Occasions |
|---|---|
| 🎩 Elegant / Luxury | Formal events, business meetings |
| 👕 Casual / Minimalist | Daily wear, outings |
| 🎨 Bold / Colorful | Parties, creative settings |
| 🎓 Smart Casual | School, university, work |

### 3. 💇 Facial Structure & Hairstyle Recommendation
- Detects facial shape: oval, round, square, heart, diamond
- Suggests compatible **hairstyles for men and women**
- Provides visual references so users can visualize results before committing

### 4. 🚶 Posture & Movement Coaching *(Phase 2)*
- Short video analysis of walking style and posture
- Personalized tips tailored by gender
- Helps users carry themselves with confidence in any setting

---

## 🤖 Why Xiaomi MiMo?

| Capability | How StyleSync AI Uses It |
|---|---|
| **Native Multimodal (Image + Text)** | Analyzing body photos and facial structure in one pass |
| **1M Context Window** | Maintaining full user style profile across sessions |
| **Agentic Reasoning** | Multi-step outfit logic based on body type + occasion + preference |
| **TTS Model** | Voice-guided posture coaching (Phase 2) |

We have previously worked with **OpenAI, Anthropic Claude, and Google Gemini APIs**. MiMo-V2.5's native vision-language fusion is the most suitable for the fine-grained visual analysis our app requires.

---

## 🗺️ Roadmap

```
Phase 1 (0–60 days)   → Body analysis + outfit recommendation MVP
Phase 2 (60–120 days) → Hairstyle recommendation + facial analysis
Phase 3 (120+ days)   → Posture coaching (video) + community features
```

---

## 🧱 Tech Stack (Planned)

- **AI Model:** Xiaomi MiMo-V2.5 (via MiMo API Platform)
- **Frontend:** React Native (iOS + Android)
- **Backend:** Node.js / Python FastAPI
- **Image Processing:** MiMo multimodal vision endpoint
- **Storage:** Firebase / Supabase

---

## 👥 Team

Small cross-functional team based in **Southeast Asia**, with backgrounds in software development, UI/UX design, and AI product development.

---

## 📊 Token Usage Estimate

| Action | Est. Tokens/Session |
|---|---|
| Body photo analysis | ~5,000 |
| Outfit recommendation generation | ~8,000 |
| Hairstyle recommendation | ~7,000 |
| Multi-turn user interaction | ~5,000 |
| **Total per session** | **~15,000–25,000** |

Target: **500–1,000 beta users** in Phase 1

---

## 🤝 Contributing

This project is part of the **Xiaomi MiMo Orbit Program**. Upon completion, we will open-source:
- Prompt engineering framework for body-type classification
- Facial geometry detection pipeline
- Southeast Asia fashion dataset (anonymized)

---

## 📬 Contact

> Project is currently in active development. Star ⭐ this repo to follow progress!

---

*Built with ❤️ using Xiaomi MiMo-V2.5 | Southeast Asia*
