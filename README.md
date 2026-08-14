# Prompt: Generate my GitHub Profile README

Copy everything below into any AI tool (Claude, ChatGPT, etc.) and it will write you a polished `README.md` for your GitHub profile repo (the repo must be named exactly your username — for Daksh, that's `Dakshified/Dakshified`).

---

Act as an expert developer-portfolio writer and GitHub README designer. Write a GitHub profile README.md for me in proper GitHub-flavored Markdown that is genuinely unique, visually dynamic, and 100% career/technical focused. Follow these rules strictly:

**Scope — career and technical only:**
- Do NOT include anything about Model United Nations, event organizing, public speaking, or content creation / social media reach. This is a purely technical/engineering profile.
- Every section should exist to answer one question for a recruiter or professor: "can this person build things and think rigorously." Nothing else.

**Tone & style — avoid the generic AI-README look:**
- No corporate buzzwords like "translating complex datasets into intelligent algorithms" or "continuous loop of learning, optimization, and automation."
- No STAR-format (Situation/Action/Result) bullet labels — write like a person describing their own work, not a resume generator.
- No empty placeholder sections (no "Recent GitHub Activity" widgets unless they'll actually render content).
- Keep emoji use minimal and purposeful — not one before every heading, and none that feel decorative rather than functional.
- Sound confident and specific, not like a template filled with adjectives.

**Make it dynamic, not just static text:**
- Use a typing/animated SVG header for the intro line (via `readme-typing-svg` from readme-typing-svg.herokuapp.com — give me the exact working image-tag syntax with my actual tagline text).
- Use live, auto-updating badges/widgets rather than static claims: GitHub stats card, top-languages card, and streak stats (via github-readme-stats and github-readme-streak-stats — give exact markdown with my username `Dakshified` filled in).
- If relevant, suggest one subtle visual structural choice (e.g. a collapsible `<details>` section for older/secondary projects so the page stays scannable) — but don't overdo layout gimmicks.
- Everything dynamic must be something that actually renders on GitHub without needing me to set up a GitHub Action — badge-service based only.

**Structure I want:**
1. An animated typing-SVG intro line — who I am, what I actually build, what I'm currently focused on (GATE CSE prep + ML/software engineering). 2-3 lines max once rendered.
2. A "Currently" line — mention I'm prepping for GATE 2027 and building toward an M.Tech, so it's fine to be honest that shipped output is lower right now.
3. 3-4 featured projects, each with ONE tight sentence on what it does and the real result — no inflated corporate framing. Use only the details below, don't invent new metrics.
4. A clean tech stack section — grouped by category, using shields.io badges, but not excessive.
5. Live GitHub stats: stats card + streak card + top languages card, side by side if possible.
6. A short "let's connect" section with GitHub, LinkedIn, email only — no other platforms.
7. One plain-stated line on the technical achievement that matters most: hackathon win + IEEE publication. Nothing else goes here.

**My real details to use (do not invent anything beyond this):**

- Name: Daksh Bhardwaj. B.Tech CS (AI), Vishwakarma Institute of Technology, Pune. CGPA 9.06. Grad 2028.
- Currently: 3rd year, preparing for GATE CSE (Feb 2027), planning M.Tech at an IIT via GATE/COAP.
- Skills: Python, C, C++, SQL, JavaScript, scikit-learn, TensorFlow (basic), PyTorch, Pandas, NumPy, Flask, FastAPI, React, Redux, MySQL, MongoDB, SQLite, Docker (basic), AWS EC2/S3, Git.
- Experience: Project Intern at Mimamsa Education Network (Jun-Dec 2025) — built their web platform in React/Redux handling 1000+ daily requests under 200ms, documented 12+ REST API endpoints (cut response time ~35%), built a QR-code complaint management system in Python that cut manual resolution time ~70%.
- Projects:
  - **Campus Trust** — blockchain certificate verification on Algorand (PyTeal + Flask), cut verification time from days to under 10 seconds across 300+ credentials, zero tampering incidents.
  - **SahAI** — ML interview assessment pipeline (Sentence Transformers, spaCy, Random Forest) for semantic answer scoring and speech evaluation, ~87% scoring accuracy across 250+ responses.
  - **ElectroLens** — real-time electronic component recognition app (MobileNetV2, Flutter, FastAPI, Gemini 1.5 Flash), 90.4% accuracy across 14 categories, <200ms latency, industry-sponsored, validated with 30 student volunteers.
  - **CAP Made Easy** — college recommendation engine (Random Forest + Reinforcement Learning) on 10,000+ Maharashtra CAP records, generated shortlists for 400+ students. Published: IEEE (link: https://ieeexplore.ieee.org/document/11434285).
- Achievements (technical only): Won a national-level hackathon at VIT Pune, finalist in 7 other national technical competitions. Published paper: IEEE (link above, via CAP Made Easy project).
- Links: GitHub github.com/Dakshified, LinkedIn linkedin.com/in/daksh-bhardwaj-40b533331, Email bhardwajdaksh1409@gmail.com.

**Output format:** Give me the complete README.md content in a single markdown code block, ready to paste directly into my GitHub profile repo.

---
