# 📝 Essay Agents — AI Writing Skill Repository

> A library of **8 deep-level AI agent skills** for writing and analyzing essays at an advanced level.  
> Built from **"Effective Writing Skills For Advanced Learners"** by S.M. Zakir Husain (all 15 chapters).  
> Designed for use with **Google Antigravity** (Claude-based AI coding assistant).

---

## 🧠 What Is This?

This repository contains a modular set of AI "skills" — structured instruction files that teach an AI agent how to think, plan, write, refine, and analyze essays using professional cognitive frameworks drawn directly from the book.

Each skill is a `SKILL.md` file that defines:
- The agent's **role and persona**
- **When** to invoke it
- **Frameworks and methodologies** (I-SEEK, CUCO, 7 Ending Types, 3-Tone Analysis, etc.)
- **Output templates** for structured, consistent responses

---

## 📦 The 8 Agents

```
                    ┌───────────────────┐
                    │   essay-master    │  ← Start here
                    │  (Orchestrator)   │
                    └────────┬──────────┘
                             │
         ┌───────────────────┼───────────────────┐
         │                   │                   │
    PHASE 1-2           PHASE 3             PHASE 4-5
         │                   │                   │
┌────────┴────────┐  ┌───────┴──────┐   ┌────────┴────────┐
│ essay-planner   │  │  paragraph-  │   │  essay-stylist  │
│ essay-architect │  │   builder    │   │  essay-refiner  │
└─────────────────┘  └──────────────┘   │  essay-flow     │
                                        │  essay-analyzer │
                                        └─────────────────┘
```

| Skill | Core Function | Key Frameworks |
|-------|--------------|----------------|
| `essay-master` | Routes and orchestrates all agents | Full pipeline, Exam Mode |
| `essay-planner` | Purpose planning + idea brainstorm | I-SEEK Model, WH-Questions, Purpose Plan Table |
| `essay-architect` | Essay structure design | Inductive/Deductive, 7 Ending Types, Beginning Strategies |
| `paragraph-builder` | Paragraph-level construction | CUCO Test, 3 Paragraph Types, 8 Orders, 6 Dev Methods |
| `essay-stylist` | Tone, style, language variety | 3-Tone Analysis, 3 Style Levels, 7 Variety Dimensions |
| `essay-refiner` | Conciseness and clarity editing | 40+ Wordy→Concise replacements, 6 Directness Tactics |
| `essay-flow` | Coherence and transitions | 5 Transition Types, 10 Marker Categories, Pronoun Audit |
| `essay-analyzer` | Full diagnostic analysis | 8-Dimension Report, /100 Score, 5 Fatal Flaw Check |

---

## 🚀 How To Use

### Installation (Antigravity)

Copy any skill folder into your Antigravity skills directory:

```
C:\Users\<you>\.gemini\antigravity\skills\
```

Example structure after installation:
```
skills/
├── essay-master/SKILL.md
├── essay-planner/SKILL.md
├── essay-architect/SKILL.md
├── paragraph-builder/SKILL.md
├── essay-stylist/SKILL.md
├── essay-refiner/SKILL.md
├── essay-flow/SKILL.md
└── essay-analyzer/SKILL.md
```

### Example Prompts

| Goal | Say This |
|------|----------|
| Write a full essay | *"Help me write an essay on Power Corrupts"* |
| Brainstorm ideas | *"I need ideas for an essay on climate change"* |
| Fix structure | *"How should I structure my essay on discipline?"* |
| Fix a paragraph | *"This paragraph feels weak, help me rebuild it"* |
| Fix wordiness | *"This is too long, cut it down"* |
| Fix flow | *"My paragraphs don't connect"* |
| Full review | *"Analyze this essay and score it out of 100"* |
| Exam emergency | *"I have 20 minutes to write on 'Democracy'"* |

---

## 🔄 The Full Writing Pipeline

```
User: "Write me a full essay on [TOPIC]"
          │
          ▼
Step 1: essay-planner    → Purpose Plan + I-SEEK + Outline
Step 2: essay-architect  → Beginning + Body sequence + Ending
Step 3: paragraph-builder→ Build each paragraph (CUCO checked)
Step 4: essay-flow       → Add transitions, fix pronoun refs
Step 5: essay-refiner    → Cut wordiness, clarify obscurity
Step 6: essay-stylist    → Tune tone, style, variety
Step 7: essay-analyzer   → Final /100 score + action plan
          │
          ▼
      FINAL ESSAY
```

---

## 📚 Book Coverage

| Chapter | Title | Skill(s) |
|---------|-------|----------|
| Ch. 1 | Purpose Planning | `essay-planner` |
| Ch. 2 | Idea Development & Thought Planning | `essay-planner` |
| Ch. 3 | Attractive Beginning | `essay-architect` |
| Ch. 4 | Unforgettable Ending | `essay-architect` |
| Ch. 5 | Variety | `essay-stylist` |
| Ch. 6 | Using Colorful & Lively Language | `essay-stylist` |
| Ch. 7 | Conciseness & Simplicity | `essay-refiner` |
| Ch. 8 | Directness & Clarity | `essay-refiner` |
| Ch. 9 | Smooth Transition | `essay-flow` |
| Ch. 10 | Writing the Modern Way | `essay-stylist` |
| Ch. 11 | Expressing Ideas the Right Way | `essay-refiner`, `essay-analyzer` |
| Ch. 12 | Tone & Style | `essay-stylist` |
| Ch. 13 | The Real Birth of an Essay | `essay-master`, `essay-analyzer` |
| Ch. 14 | The Paragraph: The Basic Unit of Composition | `paragraph-builder` |
| Ch. 15 | The Essay | `essay-architect`, `essay-master` |

---

## 📄 Key Frameworks (Quick Reference)

### I-SEEK Brainstorming Model
| Letter | Faculty | What It Generates |
|--------|---------|------------------|
| **I** | Imagination | Creative angles, hypotheticals |
| **S** | Search | Facts, data, cited research |
| **E** | Experience | Real-world personal examples |
| **E** | Expectation | Future implications |
| **K** | Knowledge | Factual substance you already know |

### CUCO Paragraph Test
| Letter | Check | What It Means |
|--------|-------|--------------|
| **C** | Completeness | Topic idea fully developed? |
| **U** | Unity | Every sentence supports the topic sentence? |
| **C** | Coherence | Flows sentence-to-sentence smoothly? |
| **O** | Order | Most logical and effective arrangement? |

### The 7 Ending Types
1. **Circular** — Returns to the opening image/idea
2. **Pseudo-Repetition** — Restates thesis in fresh, powerful language
3. **Reference to Beginning** — Echoes the hook
4. **Termination** — Deliberately abrupt for impact
5. **Summary** — Briefly recaps key points
6. **Recommendation** — Calls to action
7. **Rhythmic Variation** — Closes with dramatically paced sentences

### The 5 Fatal Essay Flaws
1. Beginning doesn't fit the ending
2. Frequent deviations from the main point
3. Thought doesn't flow beginning→end
4. Right things not said the right way (tone/style mismatch)
5. Essay is boring — no variety, no colorful language

---

## 📁 Repository Structure

```
essay-agents/
├── README.md                        ← You are here
├── skills/
│   ├── essay-master/
│   │   └── SKILL.md                 ← Master orchestrator
│   ├── essay-planner/
│   │   └── SKILL.md                 ← Planning & brainstorming
│   ├── essay-architect/
│   │   └── SKILL.md                 ← Structure designer
│   ├── paragraph-builder/
│   │   └── SKILL.md                 ← Paragraph expert
│   ├── essay-stylist/
│   │   └── SKILL.md                 ← Tone & style
│   ├── essay-refiner/
│   │   └── SKILL.md                 ← Conciseness & clarity
│   ├── essay-flow/
│   │   └── SKILL.md                 ← Coherence & transitions
│   └── essay-analyzer/
│       └── SKILL.md                 ← Full diagnostic analysis
└── docs/
    └── WALKTHROUGH.md               ← Full system documentation
```

---

## 🛡️ License

This skill repository is open for educational and personal use.  
Built on the pedagogical framework of *"Effective Writing Skills For Advanced Learners"* by S.M. Zakir Husain.

---

## ✨ Credits

- **Framework source**: *Effective Writing Skills For Advanced Learners* — S.M. Zakir Husain
- **Agent architecture**: Designed for Google Antigravity AI agent environment
- **Skill format**: Compatible with Antigravity Skills specification
