# RAG Tutor

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19447087.svg)](https://doi.org/10.5281/zenodo.19447087)

**A Personalized AI Learning Assistant for Any Course, Any Discipline**

> *"The best tutoring adapts to the learner — their pace, their gaps, their questions. RAG Tutor brings that to every student, in every subject, 24 hours a day."*

**Kiavash Bahreini, Ph.D., IEEE Senior Member**
Associate Teaching Professor, Computer Science
Knight Foundation School of Computing and Information Sciences
Florida International University
kbahrein@fiu.edu
https://github.com/KiavashBahreini7/rag-tutor

---

## What This Tool Does

RAG Tutor is a free, single-file, browser-based AI learning assistant that works for **any course in any discipline**. It uses Google Gemini to provide personalized tutoring that adapts to each student's learning history, topic mastery, and interaction patterns.

Unlike generic AI chatbots, RAG Tutor remembers what each student has studied, tracks their mastery progression across topics, offers a Socratic questioning mode, generates adaptive quizzes, prompts metacognitive reflection, and provides analytics dashboards for both students and instructors.

**No installation. No server. No subscription.** Open the HTML file in any browser, paste your free Gemini API key, and you are ready in under two minutes.

---

## What You Get

| Feature | Description |
|---------|-------------|
| Personalized Tutoring | AI adapts explanation depth based on each student's demonstrated mastery level |
| Socratic Mode | Toggle guided discovery — the AI asks questions instead of giving answers |
| Adaptive Quizzes | Auto-generated multiple-choice questions based on the student's most-studied topics |
| Topic Mastery Tracking | Visual progression from Beginner → Developing → Intermediate → Advanced → Expert |
| Session Reflections | Metacognitive prompts after substantive sessions: "What did you learn? What's still unclear?" |
| Student Dashboard | Mastery ring, topic breakdown, conversation history, activity streak, personal reflections |
| Instructor Dashboard | Topic heatmap, mastery distribution, per-student topic maps, activity table, reflection feed |
| 9 Color Themes | 6 dark themes + 3 light themes — click to switch instantly |
| Multi-Model Support | 6 Gemini models with automatic fallback when quota is reached |
| Persistent Data | All progress saved in browser localStorage — survives page refreshes and restarts |

---

## Quick Start

### Step 1: Get a Free Gemini API Key

1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Sign in with your Google account
3. Click **Create API key** → **Create API key in new project**
4. Copy the key (starts with `AIza...`)

Free tier — no credit card required. Hundreds of requests per day. Your key is stored only in your browser and is never uploaded to any server other than Google's Gemini API.

### Step 2: Download and Open the Tool

1. On this GitHub page, click the green **Code** button
2. Click **Download ZIP**
3. Extract the ZIP file
4. Double-click **RAG_Tutor.html** — it opens in your browser
5. No server, no installation, no dependencies required

### Step 3: Start Learning

1. Click **Register** and create an account
2. Paste your Gemini API key in the blue banner at the top
3. Select a model from the dropdown (Gemini 2.5 Flash recommended)
4. Click ⚡ **Test** to verify which models work with your key
5. Start asking questions about any subject

---

## Features in Detail

### Socratic Mode

Click 🏛️ **Socratic** to toggle Socratic mode. When active, the AI never gives direct answers. Instead, it asks guiding questions to help students discover answers themselves. Grounded in constructivist learning theory and Vygotsky's Zone of Proximal Development.

### Quiz Generation

Click 📝 **Quiz Me** to generate 3 multiple-choice questions based on the student's most-studied topics. Each quiz includes answer keys and explanations. Questions adapt to whatever subject the student has been studying.

### Session Reflections

When a student logs out after 3 or more questions, a reflection prompt appears: *"What did you learn today? What's still unclear?"* Reflections are saved and visible in both the student and instructor dashboards. Metacognitive monitoring is one of the strongest predictors of academic success.

### Student Dashboard

Click 👤 **My Progress** to see:
- Overall mastery ring with percentage
- Topic breakdown with progress bars and level badges
- Conversation history with timestamps
- Personal reflections
- 7-day activity streak

### Instructor Dashboard

Click 📊 **Instructor** to see:
- Summary stats: students, questions, messages, quizzes, reflections
- Topic frequency heatmap (red = high demand, indicating where students struggle)
- Student mastery distribution across all five levels
- Per-student activity table with last-active timestamps
- Per-student topic map with colored mastery badges
- Recent student reflections feed

### Color Themes

9 built-in themes (click the colored dots in the top bar):

| Theme | Style |
|-------|-------|
| Navy (default) | Classic dark blue |
| Ocean Blue | Cool marine tones |
| Emerald | Warm green and copper |
| Royal Purple | Elegant violet |
| Rose | Modern pink and slate |
| Amber Gold | Warm and authoritative |
| Light Blue | Clean light mode |
| Light Warm | Ivory and gold light mode |
| Light Mint | Fresh green light mode |

---

## Available AI Models

The tool supports 6 Google Gemini models, each with its own separate free-tier quota:

| Model | API Name | Best For |
|-------|----------|----------|
| Gemini 2.5 Flash | `gemini-2.5-flash` | Stable, general-purpose (recommended) |
| Gemini 2.5 Flash-Lite | `gemini-2.5-flash-lite` | Budget-friendly, high-throughput |
| Gemini 2.5 Pro | `gemini-2.5-pro` | High-reasoning (limited free access) |
| Gemini 3.0 Flash | `gemini-3-flash-preview` | Newest, fast multi-modal |
| Gemini 3.1 Flash-Lite | `gemini-3.1-flash-lite-preview` | High-volume, cost-sensitive |
| Gemini 3.1 Flash-Live | `gemini-3.1-flash-live-preview` | Real-time, low-latency |

**Auto-Fallback**: If your selected model hits a quota limit, the tool automatically tries all other models until one responds. The dropdown updates to show which model is active.

**⚡ Test Button**: Click to instantly check which models are available with your current API key.

---

## Adapting for Your Course

RAG Tutor works for any subject out of the box. The AI automatically detects topics from student questions and adapts its responses accordingly. No configuration is required.

For advanced customization, you can modify the system prompts in the HTML file to include course-specific instructions, required textbooks, or discipline-specific pedagogical approaches. Search for `RAG Tutor` in the code to find the prompt templates.

---

## Files in This Repository

| File | Description |
|------|-------------|
| `RAG_Tutor.html` | The tool — open in any browser |
| `RAG_Tutor_Faculty_Guide.docx` | Complete faculty guide: setup, API key, features, dashboards, models |
| `LICENSE.txt` | CC BY 4.0 license with required citation |
| `README.md` | This file |
| `qr_code.png` | QR code linking to this repository |

---

## How to Cite This Tool

Any use, adaptation, presentation, or publication referencing this tool must include the following attribution.

**APA 7th Edition:**

Bahreini, K. (2026). *RAG Tutor: A Personalized AI Learning Assistant* (Version 1.0) [Software]. Knight Foundation School of Computing and Information Sciences, Florida International University. kbahrein@fiu.edu. https://doi.org/10.5281/zenodo.19447087

**BibTeX:**
```bibtex
@software{bahreini2026ragtutor,
  author       = {Bahreini, Kiavash},
  title        = {RAG Tutor: A Personalized AI Learning Assistant},
  year         = {2026},
  version      = {1.0},
  institution  = {KFSCIS, Florida International University},
  email        = {kbahrein@fiu.edu},
  doi          = {10.5281/zenodo.19447087},
  url          = {https://github.com/KiavashBahreini7/rag-tutor},
  license      = {CC BY 4.0}
}
```

**Chicago:**

Bahreini, Kiavash. 2026. *RAG Tutor: A Personalized AI Learning Assistant.* Version 1.0. Software. Knight Foundation School of Computing and Information Sciences, Florida International University. https://doi.org/10.5281/zenodo.19447087

---

## Disclaimer

This software is provided "as is", without warranty of any kind. This tool relies on third-party AI services (Google Gemini API), which are subject to their own terms of service and availability. The author makes no guarantees regarding the accuracy or reliability of AI-generated responses. Users are responsible for verifying all information provided by the tool.

---

## License

This tool is released under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). You can use, share, and adapt for any purpose, including commercial use, as long as you give appropriate credit using the citation format above. Full license text in [LICENSE.txt](LICENSE.txt).

---

*Designed to bring personalized, AI-powered tutoring to every student in every discipline.*

**Kiavash Bahreini, Ph.D., IEEE Senior Member**
Associate Teaching Professor, Computer Science
Knight Foundation School of Computing and Information Sciences
Florida International University · CASE 337
kbahrein@fiu.edu
https://github.com/KiavashBahreini7/rag-tutor
