# 🇩🇪 German Sprint — A1 → B2 in 30 Days

A compact, real-life, multilingual German bootcamp for an Uzbek/Russian/English-speaking learner.

> **Reality check:** this project can compress the **A1→B2 syllabus, patterns, drills and exam strategy** into 30 intensive days, but no honest course can guarantee certified B2 from zero in 30 days. Treat it as a **high-intensity acceleration + diagnostic program**. For the full bootcamp, aim for **4–6 focused hours/day** and continue targeted practice after Day 30.

## What is inside

- **30-day curriculum:** A1 (Days 1–6), A2 (7–12), B1 (13–21), B2 (22–30)
- **Real-life German:** work, travel, meetings, shopping, housing, media, debates, presentations
- **UZ / RU / EN bridges:** grammar is connected to languages you already know
- **Memory hooks:** visual/emoji mnemonics instead of dry rules
- **180 high-utility words/chunks** with Uzbek, Russian, English and German examples
- **Speaking + writing + listening + reading** every day
- **Daily quiz** and retrieval practice
- **Spaced repetition:** 1 → 3 → 7 → 14 day review loop
- **Modern offline web app:** progress, flashcards, quiz, notes, TTS, focus timer, dark mode
- **Official exam practice links** and curated video/podcast/media resources

## Start the web app

Because it is dependency-free, the app works with any static server:

```bash
git clone https://github.com/therealilyas/my-german-class.git
cd my-german-class
python -m http.server 8080
```

Open `http://localhost:8080`.

You can also open `index.html` directly, although the service worker/offline mode works best over `http://localhost`.

## 30-day rhythm

**Bootcamp mode (recommended for the 30-day goal):**

| Block | Time | What you do |
|---|---:|---|
| Retrieval + flashcards | 35 min | old material first, no notes |
| Grammar + pattern drills | 60 min | understand → produce 20 original sentences |
| Listening + shadowing | 60 min | 3-pass listening, then imitate |
| Reading + sentence mining | 45 min | collect useful chunks, not random words |
| Speaking | 45 min | recorded monologue/dialogue |
| Writing | 45 min | daily task + self-correction |
| Review / quiz / error log | 30 min | repair recurring mistakes |

**Minimum sustainable mode:** 2 hours/day. Do the grammar, speaking task, 15-minute listening, flashcards and quiz.

## The learning algorithm

```text
UNDERSTAND
   ↓
NOTICE A PATTERN
   ↓
RETRIEVE WITHOUT NOTES
   ↓
USE IT IN YOUR REAL LIFE
   ↓
GET/CREATE FEEDBACK
   ↓
REPAIR THE ERROR
   ↓
REVIEW ON DAY +1, +3, +7, +14
```

A word is not considered “learned” until you can use it in a sentence **without translating first**.

## Repository map

```text
.
├── index.html              # learning dashboard
├── styles.css              # responsive UI
├── app.js                  # progress, quiz, flashcards, TTS, timer
├── manifest.json           # installable PWA metadata
├── sw.js                   # offline cache
├── data/
│   ├── course.js           # 30-day curriculum
│   └── vocab.js            # multilingual flashcard deck
├── docs/
│   ├── BOOK.md             # printable 30-day textbook
│   ├── GRAMMAR-MAP.md      # A1→B2 grammar cheat sheet
│   ├── RESOURCES.md        # videos, podcasts, tools, films, exam material
│   └── EXAM-CHECKLIST.md   # CEFR/self-test checklist
└── scripts/
    └── validate.mjs        # sanity checks for course data
```

## Source philosophy

The A1/A2 sequence is aligned with the *Momente* material supplied for this project (topics such as introductions, work, family, appointments, Perfekt, cases, `weil`, `dass`, `wenn`, advice, adjective declension and work communication). The explanations, mnemonics, drills, quizzes and web application in this repository are **original** and do not reproduce the textbook pages.

B1/B2 is an original CEFR-oriented bridge focused on high-frequency grammar, authentic input, workplace German, argumentation and Goethe-style exam practice.

## Rules for using this course

1. **Say everything aloud.** Silent recognition creates fake confidence.
2. **Record yourself daily.** Day 1, 7, 14, 21 and 30 recordings are your proof of progress.
3. **Learn chunks, not isolated words.** Learn `warten auf + Akk`, not only `warten`.
4. **Use German subtitles before English/Russian/Uzbek subtitles.**
5. **Keep an error log.** One recurring error repaired 20 times is more valuable than 100 new rules.
6. **Do not chase 100% comprehension.** At B1/B2, learn to keep listening despite unknown words.
7. **Output every day.** A course that never makes you speak cannot build speaking.

## Milestones

- **Day 6:** A1 integrated checkpoint
- **Day 12:** A2 mock
- **Day 21:** B1 mock + 5-minute speaking
- **Day 30:** B2-style timed simulation + 10-minute presentation

## License

Original project code and original educational content: MIT. Third-party resources remain under their own licenses and are linked, not copied.
