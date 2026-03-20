# Month 1 Content Generation — Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Generate complete Month 1 ("All About Me") content for the teen English course — file `docs/course/a1-month-01.md` plus a roadmap stub.

**Architecture:** Single markdown file with 4 weeks of content following the 7-block structure from the spec. Each week is self-contained. A roadmap stub outlines the 24-month plan.

**Spec:** `docs/superpowers/specs/2026-03-20-english-course-month1-design.md`

**Reference:** `/Users/dee/it-projects/my/english-path/docs/course/foundation-month-1.md` — use as style/formatting reference (adult version). Adapt tone, complexity, and topics for a 13-year-old A1 beginner.

---

### Task 1: Create roadmap stub

**Files:**
- Create: `docs/course/roadmap.md`

- [ ] **Step 1: Write roadmap.md**

Content: 24-month overview table (stage, level, months, themes). Keep it short — just the table and a note that content will be added iteratively. Use the progression plan from the spec:

```markdown
# English Course — Roadmap (A1 → C1, 24 months)

| Stage | Level | Months | Focus |
|-------|-------|--------|-------|
| Foundation | A1 → A2 | 1-6 | Basic survival English: about me, daily life, school, hobbies, simple questions |
| Building | A2 → B1 | 7-12 | Simple conversations: opinions, stories, comparisons, plans |
| Intermediate | B1 → B2 | 13-18 | Express ideas: arguments, discussions, real-world topics |
| Advanced | B2 → C1 | 19-24 | Nuanced expression: abstract topics, idioms, complex ideas |

---

*Content is generated month by month. See individual files for lesson details.*
```

- [ ] **Step 2: Commit**

```bash
git add docs/course/roadmap.md
git commit -m "docs: add 24-month course roadmap stub"
```

---

### Task 2: Write Week 1 — "Hi, I'm..."

**Files:**
- Create: `docs/course/a1-month-01.md`

- [ ] **Step 1: Write the file header and table of contents**

```markdown
# Month 1 — All About Me

**Stage:** Foundation (A1 → A2)
**Focus:** introducing yourself, talking about your day, likes, family and friends
**Pace:** one block per day, ~20-30 minutes, 6 days per week, 1 rest day

---

## Contents

- [Week 1 — Hi, I'm...](#week-1--hi-im)
- [Week 2 — My Day](#week-2--my-day)
- [Week 3 — Things I Like](#week-3--things-i-like)
- [Week 4 — My People](#week-4--my-people)
- [Month 1 Checkpoint](#month-1-checkpoint)

---
```

- [ ] **Step 2: Write Week 1 content — all 7 blocks**

Follow the spec structure exactly. Content guidelines:

**Block 1 — Core Phrases (8 phrases):**
Phrases using "to be" — introducing yourself. Teen context. Examples:
- "Hi, I'm [name]"
- "I'm 13 years old"
- "I'm from [city]"
- "I'm a student"
- "Nice to meet you"
- "I'm in 7th grade"
- "This is my first year at this school" (stretch)
- "I'm new here"

**Block 2 — Example Text (~80 words):**
A short text where a teen introduces themselves. Use all core phrases naturally. Context: new student at school or joining an online game/Discord server.

**Block 3 — Speaking Practice (8 prompts):**
- Controlled (3): "Say: Hi, I'm [your name]", "Say: I'm [your age] years old", "Say: I'm from [your city]"
- Guided (3): "What is your name?", "How old are you?", "Where are you from?"
- Free (2): "Introduce yourself to a new classmate", "Tell about yourself for 30 seconds"

Instructions at top: "Read each prompt aloud. You can record yourself on your phone."

**Block 4 — Practice Exercises (4 items):**
- Fill gap: "I ___ 13 years old." (am / is / are)
- Fill gap: "She ___ from London." (am / is / are)
- Reorder: "am / I / student / a" → "I am a student"
- Match: match 4 sentences to situations (e.g., "Nice to meet you" → "You meet someone new")

**Block 5 — Writing Task:**
"Write about yourself (50-60 words). Use the example text as a model. Include: your name, age, where you are from, what grade you are in, one more thing about you."

**Block 6 — Fun Element: Challenge**
"Introduce yourself as a famous person. Use the same phrases but pretend you are a celebrity, a game character, or a YouTuber. Example: Hi, I'm PewDiePie. I'm from Sweden. I'm a YouTuber. Nice to meet you!"

**Block 7 — Key Phrases to Remember (6):**
The most important phrases from the week to memorize.

- [ ] **Step 3: Review Week 1 against spec checklist**

Verify:
- All 7 blocks present
- Grammar: only "to be"
- Phrases, not isolated words
- Teen context
- Simple English (A1)
- Fun element present
- Self-explanatory instructions

---

### Task 3: Write Week 2 — "My Day"

**Files:**
- Modify: `docs/course/a1-month-01.md`

- [ ] **Step 1: Write Week 2 content — all 7 blocks**

**Block 1 — Core Phrases (8 phrases):**
Present Simple daily routine. Examples:
- "I wake up at 7"
- "I go to school"
- "I have lunch at school"
- "I come home at 3"
- "I do my homework"
- "I play games after school"
- "I go to bed at 10"
- "I eat breakfast with my family"

**Block 2 — Example Text (~80 words):**
A teen describing their typical school day. Morning → school → afternoon → evening.

**Block 3 — Speaking Practice (8 prompts):**
- Controlled (3): "Say: I wake up at [time]", "Say: I go to school at [time]", "Say: I go to bed at [time]"
- Guided (3): "What time do you wake up?", "What do you do after school?", "What do you do before bed?"
- Free (2): "Describe your morning", "Tell about your whole day from start to finish"

**Block 4 — Practice Exercises (4 items):**
- Fill gap: "I ___ to school every day." (go / goes / going)
- Fill gap: "She ___ up at 7." (wake / wakes / waking)
- Reorder: "at / I / up / 7 / wake" → "I wake up at 7"
- True/False about the example text (3 statements)

**Block 5 — Writing Task:**
"Write about your day (50-70 words). Start from morning, end with evening. Use time words: first, then, after that, in the evening."

**Block 6 — Fun Element: Game**
"Speed round! How many things you do in a day can you list in 60 seconds? Write them all down. Count your sentences. Can you beat 10?"

**Block 7 — Key Phrases to Remember (6):**
Select 6 key phrases from the Core Phrases above that are most useful for daily communication.

- [ ] **Step 2: Review Week 2 against spec checklist**

---

### Task 4: Write Week 3 — "Things I Like"

**Files:**
- Modify: `docs/course/a1-month-01.md`

- [ ] **Step 1: Write Week 3 content — all 7 blocks**

**Block 1 — Core Phrases (8 phrases):**
like + noun (primary), like + -ing (bonus). Examples:
- "I like pizza"
- "I love video games"
- "I don't like homework"
- "I hate waking up early"
- "My favourite game is Minecraft"
- "I like playing with my friends" (bonus -ing)
- "I really like music"
- "I don't like vegetables"

**Block 2 — Example Text (~80 words):**
A teen talking about what they like and don't like. Mix: food, games, music, school subjects, YouTube.

**Block 3 — Speaking Practice (8 prompts):**
- Controlled (3): "Say: I like [food]", "Say: I love [game]", "Say: I don't like [thing]"
- Guided (3): "What is your favourite food?", "What games do you play?", "What don't you like?"
- Free (2): "Tell about 5 things you like and 3 things you don't like", "What is your perfect day? What do you do?"

**Block 4 — Practice Exercises (4 items):**
- Fill gap: "I ___ pizza." (like / likes / liking)
- Fill gap: "He ___ video games." (like / likes / liking)
- Match: match emoji/descriptions to "I like..." / "I don't like..." / "I love..." / "I hate..."
- Reorder: "don't / I / homework / like" → "I don't like homework"

**Block 5 — Writing Task:**
"Write about things you like and don't like (50-70 words). Include: food, games or hobbies, school subjects. Use: I like, I love, I don't like, I hate, my favourite ... is ..."

**Block 6 — Fun Element: Quiz**
"Guess the person! Read 5 'I like...' / 'I don't like...' descriptions. Guess if it's: a teacher, a gamer, a sports fan, a musician, or a chef."

**Block 7 — Key Phrases to Remember (6):**
Select 6 key phrases from the Core Phrases above that are most useful for daily communication.

- [ ] **Step 2: Review Week 3 against spec checklist**

---

### Task 5: Write Week 4 — "My People"

**Files:**
- Modify: `docs/course/a1-month-01.md`

- [ ] **Step 1: Write Week 4 content — all 7 blocks**

**Block 1 — Core Phrases (8 phrases):**
have/has, possessives. Examples:
- "I have a brother"
- "My best friend is [name]"
- "He is tall and funny"
- "She has brown hair"
- "We go to the same school"
- "His name is [name]"
- "Her favourite colour is blue"
- "My family is not big"

**Block 2 — Example Text (~80 words):**
A teen talking about their best friend and family. Simple descriptions: who they are, what they look like, what they do together.

**Block 3 — Speaking Practice (8 prompts):**
- Controlled (3): "Say: My best friend is [name]", "Say: He/She is [description]", "Say: I have [family member]"
- Guided (3): "Who is your best friend? Tell about them.", "How many people are in your family?", "What do you and your friend do together?"
- Free (2): "Describe your best friend — looks, personality, what you do together", "Tell about your family"

**Block 4 — Practice Exercises (4 items):**
- Fill gap: "She ___ brown hair." (have / has / having)
- Fill gap: "___ name is Alex." (He / His / Him)
- Match: match possessives (my/his/her/our) to sentences
- Reorder: "best / my / friend / is / tall" → "My best friend is tall"

**Block 5 — Writing Task:**
"Write about your best friend or someone in your family (50-70 words). Describe: who they are, what they look like, what you do together. Use: my, his, her, have, has."

**Block 6 — Fun Element: Roleplay**
"You meet your friend's new friend at school. Introduce yourself (use Week 1 phrases!). Then describe your best friend to them. Try to say at least 5 sentences."

**Block 7 — Key Phrases to Remember (6):**
Select 6 key phrases from the Core Phrases above that are most useful for daily communication.

- [ ] **Step 2: Review Week 4 against spec checklist**

---

### Task 6: Write Month Checkpoint + final review

**Files:**
- Modify: `docs/course/a1-month-01.md`

- [ ] **Step 1: Write Month 1 Checkpoint section**

```markdown
## Month 1 Checkpoint

You finished Month 1! Let's check what you can do.

### Speaking

Record yourself on your phone (1 minute):

"Tell about yourself. Include: your name, age, where you are from, your day, things you like, and your best friend."

### Writing

Write about your best friend (60-80 words). Use phrases from all 4 weeks.

### I can... (self-check)

- [ ] I can introduce myself (name, age, city)
- [ ] I can talk about my daily routine
- [ ] I can say what I like and don't like
- [ ] I can describe my friend or family member
- [ ] I can write 50+ words about myself
- [ ] I can speak for 30+ seconds about myself
```

- [ ] **Step 2: Full file review**

Read through the entire `a1-month-01.md`. Check:
- Consistent formatting across all 4 weeks
- No grammar beyond what's specified per week
- Phrase recycling: Week 4 roleplay reuses Week 1 phrases
- All instructions are clear for a 13-year-old working alone
- ~25 unique phrases across the month
- Fun elements rotate: challenge → game → quiz → roleplay

- [ ] **Step 3: Commit**

```bash
git add docs/course/a1-month-01.md
git commit -m "docs: add Month 1 course content — All About Me (A1)"
```

---

### Quality Checklist (apply to every task)

For each week, verify:
- [ ] All 7 blocks present in order
- [ ] Only 1 grammar concept (as specified in spec)
- [ ] Phrases in context, not isolated words
- [ ] Example text is 60-100 words, teen context
- [ ] Speaking: controlled → guided → free progression
- [ ] Practice exercises: fill-gap, match, or reorder
- [ ] Writing task: 50-80 word target, clear instructions
- [ ] Fun element: doable solo, age-appropriate
- [ ] Key phrases: 5-7 items
- [ ] Simple English throughout (A1 graded)
- [ ] No complex instructions
