# Al-Zahrawi: The Father of Surgery — Interactive Project

By **Tayseer AlZier** · Victory Heights Primary School, Dubai

An interactive single-page website built for a Year 4 Islamic Studies project about
**Abu al-Qasim al-Zahrawi (936 – 1013 CE)**, the great surgeon of al-Andalus.

The whole site is a single `index.html` file with no build step, so it can be hosted
on GitHub Pages in about 5 minutes.

---

## What's inside the site

- **Arabic / English toggle** in the top right — Arabic is the default. Choice is saved in the browser so the teacher/student doesn't have to re-pick on each visit.
- **Bismillah** (بسم الله الرحمن الرحيم) banner at the very top of the page.
- **Hero** — Arabic name in calligraphy with an animated Islamic star pattern.
- **Who was he?** — the real public-domain Ernest Board painting (Wellcome Collection, 1912) framed in a museum-style gilt border, plus three "wow fact" cards.
- **Life timeline** — seven moments from his life, animated in as you scroll.
- **Kitab al-Tasrif** — about his 30-volume medical encyclopaedia, with an interactive bar of all 30 volumes (Volume 30, the surgery book, is highlighted in gold and glows). Hover or tap any volume to see what's inside.
- **Surgical instruments gallery** — 12 clickable cards with hand-drawn SVG illustrations; tap any one to open a detail card with the Arabic name and a "wow fact".
- **Map of his world** — stylised map of the Mediterranean showing how his book travelled from Córdoba → Toledo → Salerno → Bologna → Montpellier → Paris → Oxford, with animated dotted lines.
- **Al-Zahrawi & Islamic Values** *(directly addresses the 10-mark "Islamic Value Connection" rubric)* — a featured Quranic verse (Surah al-Mā'idah 5:32 about saving a life), followed by four value cards: **Seeking Knowledge** (طلب العلم), **Serving Others** (خدمة الناس), **Sincerity** (الإخلاص), and **Humility** (التواضع). Each card has the related Hadith or Qur'anic verse in Arabic, plus how al-Zahrawi lived that value.
- **Legacy** — a quote from Guy de Chauliac (a famous French surgeon who quoted al-Zahrawi over 200 times) and four big-number stats.
- **6-question quiz** — interactive multiple-choice with feedback and a final score, including a question on Islamic values.

---

## Recording Tayseer's voice notes (optional but recommended)

Every major section of the site shows a small "🎤 Listen to Tayseer narrate this part" player at the top. Until audio files are recorded, the player shows "(No narration recorded for this part yet)". Once the files are in place, the player loads them automatically and anyone visiting the site can click to hear Tayseer explain that section in his own voice.

### How to record

1. Open the site by adding `?edit=1` to the URL — e.g. `index.html?edit=1` if running locally, or `https://yourusername.github.io/al-zahrawi-project/?edit=1` if hosted.
2. Below each voice-note player, recording controls appear.
3. For each section, click **🎤 Record**, allow the microphone, speak for 20–60 seconds, then click **⏹ Stop**.
4. A preview audio player appears so Tayseer can listen back. If it's good, click the **↓ voice-CLIP** download button to save the recording as a `.webm` file. If not, click **🎤 Re-record** and try again.
5. The downloaded files will be named like `voice-hero.webm`, `voice-intro.webm`, `voice-journey.webm`, `voice-tasrif.webm`, `voice-instruments.webm`, `voice-map.webm`, `voice-values.webm`, `voice-legacy.webm`.

### Where to put the files

Create a folder named **`audio`** next to `index.html` in your project, and place each downloaded file inside it. The site automatically looks for them at `audio/voice-<section>.webm` (and tries `.mp4`, `.mp3`, `.ogg` as fallbacks if Tayseer records on a different browser like Safari).

If you're hosting on GitHub Pages, commit the `audio/` folder to the repository the same way you uploaded `index.html`. After the next GitHub Pages build (~1 minute), the play buttons will go live.

### Suggested narration prompts (Year 4 friendly)

- **Hero** *(~30 sec)* — "Hello, I'm Tayseer. Today I want to tell you about Abu al-Qasim al-Zahrawi, a Muslim doctor who lived more than a thousand years ago and changed medicine forever…"
- **Intro** *(~30 sec)* — "Al-Zahrawi was born in a beautiful palace city called Madinat al-Zahra, near Córdoba in Spain. He became one of the greatest surgeons in the world…"
- **Journey** *(~20 sec)* — "Let me take you on a journey through his life. There are seven chapters — swipe to see each one…"
- **Tasrif** *(~30 sec)* — "He wrote a giant book of medicine. It had thirty volumes — that took him fifty years! Volume 30 is the famous one about surgery…"
- **Instruments** *(~30 sec)* — "He invented more than two hundred surgical tools. Click the leather bag to see what was inside…"
- **Map** *(~30 sec)* — "His ideas didn't stay in Spain. Watch how they travelled across the Mediterranean to all the great universities of Europe…"
- **Islamic Values** *(~45 sec — the most important one)* — "What I love about al-Zahrawi is how he lived his Islamic values. He sought knowledge, served everyone equally, was sincere in his work, and was humble. The Qur'an says whoever saves one life saves all of humanity…"
- **Legacy** *(~30 sec)* — "Even today, doctors all over the world still use the tools and ideas of al-Zahrawi. He proved that one person, guided by Islamic values, can change the whole world…"

That's about 4 minutes of total audio — very doable in one or two evenings.

## Hosting on GitHub Pages (step-by-step)

You need a free GitHub account: <https://github.com/signup>

### 1. Create a new repository

1. Go to <https://github.com/new>
2. **Repository name:** something like `al-zahrawi-project`
3. Set it to **Public**
4. Tick **"Add a README file"**
5. Click **Create repository**

### 2. Upload the site

1. On the new repo page, click **Add file → Upload files**
2. Drag in the `index.html` file (the README.md is optional — you can drag that in too)
3. Scroll down and click **Commit changes**

### 3. Turn on GitHub Pages

1. In the repo, click **Settings** (top right of the repo menu)
2. In the left sidebar, click **Pages**
3. Under **Build and deployment → Source**, choose **Deploy from a branch**
4. Under **Branch**, choose **main** and folder **`/ (root)`**, then click **Save**
5. Wait about 1–2 minutes, then refresh the page — GitHub will show a green box with the live link

It will look like:

```
https://<your-username>.github.io/al-zahrawi-project/
```

Share that link with the teacher and classmates. Done!

### Tip — custom-looking link

If the repo is named exactly **`<your-username>.github.io`** (e.g. `naserzeer.github.io`),
the site will live at `https://<your-username>.github.io/` — no subfolder. Looks more professional.

---

## Running the site locally (no internet needed)

Just double-click `index.html`. It opens in any web browser. The Google Fonts and one
small online image reference will simply not appear if there's no internet, but
everything else works.

For the smoothest experience, host on GitHub Pages so the fonts load and the link
can be shared.

---

## Presenting tips for the project

- Open the page on a school laptop or iPad in full-screen mode (press **F11** on Windows or **⌃⌘F** on a Mac).
- Walk through it section by section: introduce him → timeline → his book → tools (click 2 or 3 to demonstrate) → the map → **Islamic Values** (slowly, with feeling — that's the 10-mark section) → finish with the quiz so classmates can join in.
- The map's dotted lines animate every time you scroll into it — a nice "wow" moment.
- Use the AR/EN toggle in the top corner if you want to demonstrate switching to Arabic for the teacher.

## How the site addresses the grading rubric (50 marks)

| Criterion (max marks) | Where it's addressed |
| --- | --- |
| Content accuracy & understanding (15) | Timeline, Kitab al-Tasrif section, Instruments gallery, Map, Legacy — all sourced from Britannica, PubMed Central, Wikipedia |
| Creativity & innovation (10) | Animated hero star, Islamic manuscript styling, interactive instruments, scrolling timeline, animated map paths, quiz |
| Islamic value connection (10) | Bismillah banner at top, dedicated "Al-Zahrawi & Islamic Values" section with Quran 5:32 and four value cards (knowledge, service, sincerity, humility) — each tied to a Hadith or Qur'anic verse |
| Presentation & communication (10) | Student delivers the presentation in person; the site is the supporting visual |
| Overall effort & quality (5) | Polished design, bilingual AR/EN, real public-domain painting, hand-drawn instrument SVGs |

---

## Credits & sources

Researched from Wikipedia, Encyclopædia Britannica, PubMed Central
(*"Abu Al Qasim Al Zahrawi (Albucasis): Pioneer of Modern Surgery"*),
Muslim Heritage, and Frontiers for Young Minds.

All illustrations are simple SVGs drawn from scratch (no copyrighted images).
The site uses Google Fonts: *Cinzel*, *Cormorant Garamond*, *Amiri*, *Lato*.
