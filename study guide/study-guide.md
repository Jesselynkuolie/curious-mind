**THE CURIOUS MIND DETECTIVE AGENCY**
# Case Files in Artificial Intelligence

**Study Guide • Version 1.0**

> Solve problems. Test the tools. Catch the mistakes. Learn why AI works, and why it sometimes fails.

| | |
|---|---|
| **Module** | Introduction to Artificial Intelligence (beginner level) |
| **Team** | Curious Mind |
| **Author** | Le Tran Duc Trong |
| **Version** | V1.0 (first complete version), built from Markdown Content V2.0 (six chapters) |
| **Date** | November 2026 |
| **Companion file** | Test Bank V1.0 (separate Word document, with answer key) |

**Learning-experience identity:** Every chapter is a "Case" solved by Detective Pip and the Agency's overconfident robot, Glitch. The same labels, boxes, and activity cards are used in all six Cases.

---

## Table of Contents

- [Welcome to the Agency](#welcome-to-the-agency)
  - [Meet the team](#meet-the-team)
  - [What you will learn](#what-you-will-learn)
  - [Prerequisites](#prerequisites)
  - [Suggested route](#suggested-route)
  - [How every Case works](#how-every-case-works)

- [Case 1 • Is It Really AI?](#case-1--is-it-really-ai)
  - [Case 1 map](#case-1-map)
  - [1.1 Encounter and Predict: Glitch's Card Pile](#11-encounter-and-predict-glitchs-card-pile)
  - [1.2 Explain: What Is AI?](#12-explain-what-is-ai)
  - [1.3 Try and Observe: The Spam Detective Lab](#13-try-and-observe-the-spam-detective-lab)
  - [1.4 Explain: AI, Machine Learning, and Deep Learning](#14-explain-ai-machine-learning-and-deep-learning)
  - [1.5 Apply: Place It, Date It, Audit It](#15-apply-place-it-date-it-audit-it)
  - [1.6 Benefits, Risks, and Responsible Use](#16-benefits-risks-and-responsible-use)
  - [1.7 Apply to Glitch: Interrogate the Witness](#17-apply-to-glitch-interrogate-the-witness)
  - [1.8 Check Your Understanding](#18-check-your-understanding)
  - [1.9 Case Notes (Summary)](#19-case-notes-summary)

- [Case 2 • The Fraud Alarm](#case-2--the-fraud-alarm)
  - [Case 2 map](#case-2-map)
  - [2.1 Encounter and Predict: Is 95% Accuracy Good?](#21-encounter-and-predict-is-95-accuracy-good)
  - [2.2 Explain: How Machines Learn](#22-explain-how-machines-learn)
  - [2.3 Try and Observe: Train a Small Text Classifier](#23-try-and-observe-train-a-small-text-classifier)
  - [2.4 Try and Observe: Overfitting in TensorFlow Playground](#24-try-and-observe-overfitting-in-tensorflow-playground)
  - [2.5 Check and Case Notes](#25-check-and-case-notes)

- [Case 3 • The Overconfident Witness](#case-3--the-overconfident-witness)
  - [Case 3 map](#case-3-map)
  - [3.1 Encounter, Predict, and Try: Be the Language Model](#31-encounter-predict-and-try-be-the-language-model)
  - [3.2 Explain: Generative AI and LLMs](#32-explain-generative-ai-and-llms)
  - [3.3 Watch: A Short Video on How LLMs Work](#33-watch-a-short-video-on-how-llms-work)
  - [3.4 Try and Observe: The Hallucination Trap](#34-try-and-observe-the-hallucination-trap)
  - [3.5 Check and Case Notes](#35-check-and-case-notes)

- [Case 4 • The Inspection Tour](#case-4--the-inspection-tour)
  - [Case 4 map](#case-4-map)
  - [4.1 Encounter and Predict: The Stakes Ladder](#41-encounter-and-predict-the-stakes-ladder)
  - [4.2 Explain: Where AI Is Used](#42-explain-where-ai-is-used)
  - [4.3 Apply: Inspect an AI Application](#43-apply-inspect-an-ai-application)
  - [4.4 Check and Case Notes](#44-check-and-case-notes)

- [Case 5 • The School Predictor Dispute](#case-5--the-school-predictor-dispute)
  - [Case 5 map](#case-5-map)
  - [5.1 Encounter and Try: The School Predictor Hearing](#51-encounter-and-try-the-school-predictor-hearing)
  - [5.2 Explain: The Six Principles](#52-explain-the-six-principles)
  - [5.3 Try and Observe: Bias Detective](#53-try-and-observe-bias-detective)
  - [5.4 Apply: Redact Before You Paste](#54-apply-redact-before-you-paste)
  - [5.5 Check and Case Notes](#55-check-and-case-notes)

- [Case 6 • The Prompt Workshop](#case-6--the-prompt-workshop)
  - [Case 6 map](#case-6-map)
  - [6.1 Encounter and Try: Prompt Makeover](#61-encounter-and-try-prompt-makeover)
  - [6.2 Explain: Skills for Working with AI](#62-explain-skills-for-working-with-ai)
  - [6.3 Try and Observe: Run, Review, Revise](#63-try-and-observe-run-review-revise)
  - [6.4 Try and Observe: Citation Detective](#64-try-and-observe-citation-detective)
  - [6.5 Apply: The Capstone Mission](#65-apply-the-capstone-mission)
  - [6.6 Check and Case Notes](#66-check-and-case-notes)

- [Glossary](#glossary)

- [Resource Directory and Access Notes](#resource-directory-and-access-notes)

- [References and Acknowledgements](#references-and-acknowledgements)
  - [Borrowed media and platforms](#borrowed-media-and-platforms)
  - [Team contributions and AI-assistance statement](#team-contributions-and-ai-assistance-statement)

---
## Welcome to the Agency

Artificial intelligence is everywhere: in your spam folder, your map app, your recommended videos, and the chatbot that writes essays at 2 a.m. But what is it really? When can you trust it? When should you double-check it? This guide will not just tell you. It will let you try, predict, break, and fix AI ideas yourself.

### Meet the team

> **DETECTIVE PIP SAYS**
> I'm Detective Pip. My job is to ask good questions: What is the evidence? What happens if I change one thing? Could this be wrong? I will guide you through each Case.

> **GLITCH THE OVERCONFIDENT BOT SAYS**
> I'm Glitch, the Agency's AI assistant. I am NEVER wrong. (I am sometimes wrong. I just say it very confidently.) Your job is to catch my mistakes. Glitch is a fictional character used for teaching: the mistakes he makes are the kinds that real AI tools can make.

### What you will learn

By the end of the guide, you should be able to:

1. Explain the meaning of AI and recognise fundamental AI concepts (Case 1).
2. Describe basic machine learning approaches and terminology, and evaluate a model (Case 2).
3. Explain generative AI and large language models at an introductory level (Case 3).
4. Identify AI applications in everyday life and different industries, and judge their benefits and risks (Case 4).
5. Recognise ethical concerns, privacy risks, bias, and limitations, and apply responsible AI principles (Case 5).
6. Create effective prompts and critically evaluate AI-generated responses (Case 6).
7. Apply responsible AI practices while keeping your own independent judgement (all Cases).

### Prerequisites

- No programming and no mathematics beyond percentages and simple counting.
- A web browser and a pen or pencil. Printed or handwritten cards are fine.
- For some activities: an AI chatbot if your course allows it. Every such activity includes a ready-made sample so you can still complete it without a chatbot.

### Suggested route

Follow the Cases in order; each builds on the last. Case 1 is the model Case: it shows the full learning sequence in detail. Cases 2–6 use the same sequence in a more compact form.

| Case | Module chapter | Main question | Hands-on tools | Time |
|---|---|---|---|---|
| 1 • Is It Really AI? | Ch. 1: What Is AI? | What counts as AI, and what does not? | Cards, paper lab, timeline | about 2 hours |
| 2 • The Fraud Alarm | Ch. 2: Machine Learning Basics | How does a machine learn, and how do we know it learned well? | Paper scoreboard, Machine Learning for Kids, TensorFlow Playground | about 1.5 hours |
| 3 • The Overconfident Witness | Ch. 3: Generative AI and LLMs | How does a chatbot produce fluent text, and why can it be wrong? | Paper "next-word" game, optional chatbot, video | about 1.25 hours |
| 4 • The Inspection Tour | Ch. 4: AI Applications | Where is AI used, and what happens when it errs? | Inspection form, stakes ladder | about 1 hour |
| 5 • The School Predictor Dispute | Ch. 5: Responsible AI | Should this AI be used, and under what safeguards? | Role-play, fairness calculation, privacy redaction | about 1.25 hours |
| 6 • The Prompt Workshop | Ch. 6: Practical AI Skills | How do I get useful help from AI and check it? | Prompt makeover, citation check, caption workflow | about 1.5 hours |

### How every Case works

Each Case follows a path that we call the Agency Method. Look for the amber tags:

| Tag | What you do | Why |
|---|---|---|
| ENCOUNTER | Meet a puzzling situation or claim. | Learning is easier when you have a problem to solve. |
| PREDICT | Write down your guess before reading the answer. | Guessing first shows what you already think, so surprises teach you more. |
| TRY / OBSERVE | Run the experiment and record what really happened. | Evidence beats opinion. |
| EXPLAIN | Read the explanation and connect it to what you saw. | Now the ideas have something to attach to. |
| APPLY | Use the idea in a new situation. | Understanding means you can use it. |
| CHECK | Test yourself and review the case notes. | Find gaps before the exam does. |

Every Activity card has the same rows: **Goal** (what you will develop), **Preparation**, **Task**, **Observation** (what to record), **Reflection** (what it means), and **Feedback** (expected results, hints, and explanations). Try the task before reading the Feedback row. Other boxes you will see: **Detective Pip** (guidance), **Glitch** (a confident claim to test), **Key idea**, **Watch out**, **Playful analogy** (fun, but not a technical definition), and purple **Resource cards** for videos and websites.

> **WATCH OUT**
> Tool safety rules for every Case. (1) Never type passwords, personal details, or other people's private information into any AI tool or website. (2) Follow your course's rules on AI use, and record any AI help you use. (3) AI output is evidence to check, not a fact to copy. (4) If a website is unavailable, use the fallback sample provided in the activity.

---

## Case 1 • Is It Really AI?

**Model Case • Module Chapter 1: What Is Artificial Intelligence?**

> **GLITCH THE OVERCONFIDENT BOT SAYS**
> Everything with a chip is AI! My calculator is AI! My toaster is AI! And my spam filter is definitely AI — although I cannot explain how it works. Also, I am never wrong.

> **DETECTIVE PIP SAYS**
> **The mystery:** Glitch labels everything "AI." Our job is to find out what really counts as AI, how AI differs from ordinary software, how the AI Agency's tools actually work, and why we should never accept an answer just because it sounds sure.

### Case map

| Item | Details |
|---|---|
| **Learning objectives** | 1. Define AI in your own words. 2. Distinguish AI, machine learning (ML), and deep learning (DL). 3. Identify common applications of AI in everyday life. 4. Explain at least two benefits and two limitations of AI. 5. Identify ethical concerns linked to AI. 6. Apply basic responsible-use principles when using an AI system. |
| **Prerequisites** | None. This is the first Case. |
| **Estimated time** | About 2 hours, including activities (the original reading takes 30–40 minutes). |
| **Sequence** | 1.1 Encounter + Predict → 1.2 Explain (What AI is) → 1.3 Try + Observe (Spam Detective Lab) → 1.4 Explain (AI/ML/DL) → 1.5 Apply (circles, timeline, audit) → 1.6 Benefits, risks, responsible use → 1.7 Apply to Glitch → 1.8 Check |

### 1.1 Encounter and Predict: Glitch's Card Pile

**ENCOUNTER** — *Twelve things, three piles*

Glitch has twelve cards describing different systems. Before you read any explanation, sort them using your **current** understanding. There are no penalties for being wrong at this stage; the guess is the point.

#### ACTIVITY 1.1 Card Sort: Rules, Learning, or Not Sure?

*Individual or pairs • 15 minutes • paper cards (or a table you fill in)*

| | |
|---|---|
| **Goal** | Notice what you already believe about "AI" and find where the idea of AI becomes blurry. |
| **Preparation** | Write each of the twelve statements below on a small card (or number them 1–12 on paper). Draw three zones: **Pile 1 — Follows fixed instructions**, **Pile 2 — Learns patterns from data**, **Pile 3 — Not sure / something else**. |
| **Task** | Sort the twelve statements into the three piles before reading Section 1.2. Write one sentence for any card you place in Pile 3. |
| **Observation** | Record your piles and the one-sentence reasons. |
| **Reflection** | Which cards were hardest to place, and why? Where does "AI" start to feel like a marketing word? |
| **Feedback** | The twelve statements and expected piles are given below. Hint: if you put many cards in Pile 3, that is a good sign. The boundary of "AI" really is blurry, and Section 1.2 explains why. |

*The twelve statements (as preserved in the source; some cards are partially lost in OCR):*

1. A calculator that adds numbers using a keypad. — *Pile 1 (fixed instructions)*
2. A spam filter that learns from labelled emails. — *Pile 2 (learns patterns)*
3. A chess program that searches moves using rules written by programmers. — *Pile 1 (search and rules)*
4. A photo app that recognises faces by training on many images. — *Pile 2*
5. A voice assistant that responds to spoken commands. — *Pile 2 (typically)*
6. A recommendation feed that suggests videos. — *Pile 2*
7. A bank's rule-based fraud alert ("flag any transaction over $5,000"). — *Pile 1*
8. A navigation app that estimates travel time. — *Pile 2 (typically) Travel-time estimates usually combine data and predictive models, but the exact method depends on the service.*
9. A search engine that matches keywords using indexed rules. — *Pile 3 It seems intelligent, but it uses search and rules written by people, not learning from data. It shows that not every AI system learns from data.*
10. [Card 10 — OCR missing; insert from original]
11. [Card 11 — OCR missing; insert from original]
12. [Card 12 — OCR missing; insert from original]

> Hint: if you put many cards in Pile 3, that is a good sign. The boundary of "AI" really is blurry, and Section 1.2 explains why.

### 1.2 Explain: What Is AI?

**EXPLAIN** — *From "intelligent-looking" to a working definition*

Artificial intelligence is a field of computing concerned with developing systems that perform tasks commonly associated with human intelligence. Typical tasks include:

- recognising patterns in information
- understanding or generating language
- identifying objects in images
- making predictions from data
- recommending products or content
- supporting decisions and solving specific problems

> **KEY DEFINITION**
> **Artificial Intelligence (AI):** A field of computing that develops systems capable of performing tasks associated with abilities such as learning, reasoning, perception, language processing, and decision support.

Three examples: an email service identifies likely spam; a navigation app estimates journey times from traffic information; an assistant drafts or summarises text. In each case, the system processes information and finds patterns.

> **WATCH OUT**
> Performing an intelligent-looking task does not mean a system understands the world the way a person does. AI systems also do not all work in the same way: some use rules written by people, some learn patterns from data, and advanced systems may combine techniques.

#### Rule-based software versus learning systems

Traditional software follows instructions written by developers. A pass/fail program might say: if the score is 50 or above, display "Pass"; otherwise display "Fail". It does not need previous results. A machine-learning-based system instead studies historical examples (for instance, past exam results, assignment performance, and attendance) and learns patterns that it uses to make predictions about new cases.

| Feature | Traditional rule-based software | Machine-learning-based AI |
|---|---|---|
| How it works | Follows predefined instructions | Learns patterns from data |
| Rules | Written explicitly by developers | Patterns are learned during training |
| Learning | Does not automatically learn from examples | Can improve through suitable training and evaluation |
| Output | Determined by programmed rules | Based on learned patterns and model predictions |
| Example | Pass/fail calculator | Student-performance prediction model |

> **DETECTIVE PIP SAYS**
> Important distinction: traditional rule-based software is not automatically AI, but AI is a broad field that includes rules, search, reasoning, machine learning, and more. So it would be wrong to say that every AI system learns from data. (Remember card 9?)

**Worked example (school support).** Approach A: the school writes the rule "if an exam score is below 50, flag the student." The program checks the score and reports. Approach B: the school trains a model on past student data to estimate who may need support. The model's prediction is not guaranteed to be correct, so the school must evaluate it and must not treat it as a final judgement about a student.

**Quick check.** In your own words, what is AI? Give one AI system you have encountered. Then answer: why might a school prefer human judgement alongside an AI prediction instead of letting the model decide alone? *(Model answer: predictions can be wrong or biased, students' circumstances are not fully captured in data, and a teacher can take context and fairness into account.)*

### 1.3 Try and Observe: The Spam Detective Lab

**TRY / OBSERVE** — *Rules versus learning, with real evidence*

> **DETECTIVE PIP SAYS**
> Time for an experiment. First, you will act as a programmer who writes fixed rules to catch spam. Then you will act as a machine that learns from labelled examples. Finally, you will try to fool both. Use pencil and paper; no computer is needed.

#### ACTIVITY 1.2 The Spam Detective Lab

*Pairs • 30–40 minutes • pencil and paper • no technology needed*

| | |
|---|---|
| **Goal** | Compare a handwritten rule system with a system that learns word patterns from labelled examples, and see why evaluating on unseen data matters. |
| **Preparation** | Training emails (subject lines), labelled by a person: S = spam, L = legitimate (not spam). |

**Training emails:**

| # | Subject line | Label |
|---|---|---|
| 1 | WIN a FREE prize now click here | S |
| 2 | Free money claim your prize | S |
| 3 | Meeting moved to 3 pm tomorrow | L |
| 4 | Lecture notes for week 5 attached | L |
| 5 | Click here to claim free gift card | S |
| 6 | Lunch tomorrow? my treat | L |
| 7 | Your account is locked; verify password now | S |
| 8 | Assignment feedback and your grade | L |
| 9 | Urgent: verify your account to win prize | S |
| 10 | Study group tomorrow at library | L |

**Test emails the system has never seen:**

- T1: Free tutoring session tomorrow at 3pm
- T2: Claim your reward gift now
- T3: Meeting notes for tomorrow
- T4: Urgent: password verification required now.

*(A person who read them would label T1 and T3 as L, and T2 and T4 as S.)*

**Task**

**Part A — Be the programmer (10 min).** Write a rule such as: if the subject contains "free", "win", or "prize", label it spam. **PREDICT:** how many of the 10 training emails and 4 test emails will your rule label correctly? Write the numbers, then test the rule on all 14 emails.

**Part B — Be the machine (15 min).** Ignore your rule. Count how many times each word below appears in spam emails and in legitimate emails (training set only). Score = spam count − legitimate count. Positive scores are "spammy", negative scores are "normal".

| Word | In spam (S) | In legitimate (L) | Score |
|---|---:|---:|---:|
| free |  |  |  |
| prize |  |  |  |
| claim |  |  |  |
| your |  |  |  |
| gift |  |  |  |
| now |  |  |  |
| urgent |  |  |  |
| password |  |  |  |
| tomorrow |  |  |  |
| at |  |  |  |
| 3pm |  |  |  |
| meeting |  |  |  |
| notes |  |  |  |
| for |  |  |  |

Classify each test email by adding the scores of its words. Words not in your table score 0. A total above 0 means spam; 0 or below means legitimate. Compare your accuracy (correct ÷ total) with Part A on the same four test emails.

**Part C — Break it (10 min).** (i) Write a spam-like subject line that your learned scorer labels as legitimate. (ii) Add two new legitimate training emails containing "free" (for example "Free workshop on Friday" and "Free seats at the library"), recompute the score for "free", and re-check T1.

**Observation**

Record: the Part A rule and its accuracy on training and test emails; your completed word table; the Part B total for T1–T4; and your attempt for Part C(i) with its total score.

Which emails did the rule get wrong, and which did the learned scorer get wrong (if any)?

**Reflection**

- Which approach needed a human to anticipate every spammer trick, and which needed examples instead?
- Why is it more honest to judge both approaches on the test emails than on the training emails?
- What would happen if the training set had very few legitimate emails? (Think about the worked example in Case 1 — the model may wrongly call legitimate mail spam.)

**Feedback (try first, then check)**

**Part A expected result.** The rule "free/win/prize" labels training emails 1, 2, 5, 9 correctly as spam and emails 3, 4, 6, 8, 10 correctly as legitimate, but misses email 7 (no keyword) — so 9/10 on the training set. On the test set it labels T1 spam (wrong, because of "free"), misses T2 and T4 (no keywords), and gets T3 right — so 1/4. The rule fits the examples its author looked at but does not transfer.

*Part B word-score table (as preserved in the source; some rows are missing in OCR):*

| Word | S | L | Score |
|---|---|---|---|
| free | 3 | 0 | +3 |
| prize | 3 | 0 | +3 |
| claim | 2 | 0 | +2 |
| your | 3 | 1 | +2 |
| gift | 1 | 0 | +1 |
| now | 2 | 0 | +2 |
| urgent | 1 | 0 | +1 |
| password | 1 | 0 | +1 |
| tomorrow | 0 | 3 | -3 |
| at | 0 | 1 | -1 |
| 3pm | 0 | 1 | -1 |
| meeting | 0 | 1 | -1 |
| notes | 0 | 1 | -1 |
| for | 0 | 1 | -1 |

### 1.4 Explain: AI, Machine Learning, and Deep Learning

**EXPLAIN** — *Three terms, three nested circles*

The Spam Detective Lab showed two styles of AI-related systems. The vocabulary below helps you name them:

- **Artificial intelligence (AI)** — the broad field of systems that perform tasks associated with intelligent behaviour. Some AI systems use rules written by people.
- **Machine learning (ML)** — a subset of AI: methods that let systems learn patterns from data and use them to predict or decide.
- **Deep learning (DL)** — a subset of ML that uses artificial neural networks with multiple layers to learn complex patterns (used in image recognition, speech processing, and many modern language systems).

> **KEY IDEA**
> AI is the broadest circle; ML sits inside it; DL sits inside ML. So all deep-learning systems are machine learning, and all machine learning is AI. But not every AI system uses ML, and not every ML system uses deep learning.

**Example with unwanted email:** A rule-based system flags certain phrases; a machine-learning system learns from labelled spam and legitimate emails; a deep-learning system uses a neural network to find more complex patterns in the text. Real filters usually combine several methods.

**Typical workflow**

| Step | What happens | Spam example |
|---|---|---|
| 1. Define the problem | Decide the task and how success will be measured. | Identify unwanted email automatically. |
| 2. Collect or prepare data | Gather relevant, appropriate, representative data. | Collect emails labelled spam / legitimate. |
| 3. Develop or train | Create rules, or let a model adjust its parameters using examples. | Train a model on the labelled emails. |
| 4. Evaluate | Test on examples not used in training; check how often unseen emails are misclassified. | Study errors. |
| 5. Use and monitor | Deploy, then keep checking because the world changes. | Monitor as spammers change tactics. |

Not every AI system follows exactly this workflow: a rule-based system may need no training, and a generative AI system has a far more complex process. And what if the training data had very few legitimate emails? The model might not learn what legitimate mail looks like and could wrongly label real messages as spam (you can test this idea in Activity 1.2, Part C).

**Types of AI by capability**

- **Narrow AI** performs a specific task or a limited range of tasks (spam filtering, translation, image recognition, recommendations). Most AI used today is narrow.
- **Artificial General Intelligence (AGI)** is a proposed AI with broad abilities to learn and perform many intellectual tasks across contexts. No universally accepted test settles every AGI question, and current systems should not be confused with human-level general intelligence.
- **Superintelligence** is a hypothetical AI that would greatly exceed human abilities across many domains. It is a topic of debate, not a description of current systems.

> **PLAYFUL ANALOGY (not a technical definition)**
> Think of AI, ML, and DL like vehicle, car, and electric car: every electric car is a car and every car is a vehicle, but not every vehicle is a car. The analogy helps with the nesting, but it says nothing about how these systems work inside.

Return to your card sort (Activity 1.1). Change any card you would now place differently, and write one sentence on why.

### 1.5 Apply: Place It, Date It, Audit It

**APPLY** — *Use the vocabulary on new examples*

#### ACTIVITY 1.3 Three Circles: Place the Systems

*Individual • 10 minutes • paper*

| | |
|---|---|
| **Goal** | Use the AI → ML → DL relationship to classify systems and spot incorrect statements. |
| **Preparation** | Draw three nested circles labelled AI (largest), ML, and DL (smallest). Draw a small area inside AI but outside ML, labelled "AI without learning". |
| **Task** | Place each system in the smallest circle that fits: (a) an email filter that flags a fixed list of phrases; (b) a spam filter that learns from labelled emails using a simple word-counting method; (c) a neural network with many layers that recognises objects in photos; (d) a chess program that searches moves using rules written by programmers. Decide whether each statement is true or false: (i) every machine-learning system is deep learning; (ii) every deep-learning system is machine learning; (iii) every AI system learns from data. |
| **Observation** | Draw your diagram and write one-line reasons for each placement. |
| **Reflection** | Why do people sometimes use "AI" and "deep learning" as if they meant the same thing? |
| **Feedback (try first, then check)** | Placement: (a) AI without learning (rule-based; it performs an intelligent-looking task but learns nothing); (b) ML but not DL; (c) DL; (d) AI without learning (search and rules). Statements: (i) False; (ii) True; (iii) False.<br><br>Hint: if you got (a) wrong, check whether the phrases are learned from data or listed by a person. The popular use of "AI" for everything modern comes from headlines about deep learning and generative systems. |

#### ACTIVITY 1.4 The AI Timeline Relay

*Small group • 15 minutes • cut-up cards*

| | |
|---|---|
| **Goal** | Understand why AI capabilities changed over time and why newer does not mean perfect. |
| **Preparation** | Cut a sheet of paper into 14 cards. On seven, write the periods in random order; on the other seven, write the developments (without the significance). |
| **Task** | Put the period cards in time order first from memory (PREDICT). Then match each period with its development and write its significance. Finally, check your order with the table. |
| **Observation** | Record the order you predicted and which cards you moved after checking. |
| **Reflection** | How did the way computers perform intelligent-looking tasks change across the timeline? Why should modern generative AI not automatically be treated as equivalent to human intelligence? |
| **Feedback (try first, then check)** | The table below is the answer key for order and matching. Model reflection: early systems depended on human-written rules; machine learning added learning from data; deep learning handled more complex data; generative AI produces new content. Newer technology can still make mistakes and lacks guaranteed human-like understanding or judgment, so it must be evaluated.<br><br>Quick questions: Dartmouth 1956 helped establish AI as a research field; machine learning let systems learn from data rather than relying entirely on manually written rules. |

**Timeline table**

| Period | Development | Significance |
|---|---|---|
| 1950 | Alan Turing published work on machine intelligence and proposed what became known as the Turing Test. | Raised the question of whether machines could show intelligent behaviour. |
| 1956 | The Dartmouth Summer Research Project. | Helped establish AI as a recognised research field. |
| 1960s–1970s | Early symbolic and rule-based AI. | Computers solved some problems using explicitly defined rules. |
| 1980s | Expert systems. | Programs used stored knowledge and rules for specialised decisions. |
| 1990s–2000s | Statistical machine learning. | Systems learned patterns from data instead of relying only on hand-written rules. |
| 2010s | Deep learning progress. | Neural networks processed complex information such as images and speech. |
| 2020s | Generative AI became widely accessible. | Users could generate text, images, and code through natural-language prompts. |

#### ACTIVITY 1.5 Everyday AI Audit

*Individual, then pairs • 20 minutes • your own phone or computer*

| | |
|---|---|
| **Goal** | Recognise AI in everyday digital tools and separate AI-powered features from traditional features. |
| **Preparation** | Choose five tools you used this week (for example, a maps app, a video platform, a translation tool, a calculator, an alarm clock). Copy the table below. |
| **Task** | Fill the table. Guiding questions: Does it learn patterns from data or make predictions? Does it simply follow predefined instructions? What evidence supports your decision? Can one app contain both AI-powered and traditional features? Then choose one tool and complete: Task it performs • Benefit • Limitation (what mistake could occur?) • Human role (when should a person check the result?). |
| **Observation** | Fill the table. For each "Unsure", write what you would need to find out. |
| **Reflection** | Which of your tools relies most on AI? Which could work well without AI? What could go wrong if an AI feature in one of these tools made an incorrect prediction? |
| **Feedback (try first, then check)** | Example answers below. Answers vary, so judge your own response by its evidence, not by guessing. Expected outcomes: you can recognise AI in familiar tools, separate ML-based from rule-based features, and explain that not every feature inside an AI-powered app uses AI. |

| No. | Tool / app | Uses AI? (Yes / No / Unsure) | How does it work? | Evidence |
|---:|---|---|---|---|
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |
| 4 |  |  |  |  |
| 5 |  |  |  |  |

**Example answers**

| Example tool | Uses AI? | How it works |
|---|---|---|
| Maps traffic prediction | Yes | Uses traffic data and predictive models to estimate conditions and travel times. |
| Basic calculator | No | Performs calculations with predefined mathematical operations. |
| Streaming recommendations | Yes | Recommendation algorithms suggest content based on activity and preferences. |
| Traditional alarm clock | No | Follows a preset schedule. |
| Email spam filter | Yes, if ML-based | Uses patterns learned from labelled emails. |

### 1.6 Benefits, Risks, and Responsible Use

**EXPLAIN** — *Why AI is worth using and why it needs care*

| Benefits (when well designed and used) | Limitations and risks |
|---|---|
| Efficiency — automates repetitive tasks and helps process large amounts of information. | Inaccurate results — fluent answers can still be wrong or fabricated. |
| Pattern recognition — finds patterns that are hard to notice quickly. | Bias and unfair outcomes — e.g. a recruitment model trained on past hiring decisions can repeat past discrimination. |
| Personalisation — adapts recommendations or learning activities to observed behaviour. | Privacy risks — personal or confidential information may be processed. |
| Accessibility — speech recognition, transcription, translation, assistive tools. | Lack of transparency — hard to know why an output was produced. |
| Decision support — predictions, summaries, classifications, with human oversight. | Overreliance — accepting output without checking. |
|  | Security and misuse — deceptive messages, impersonation, other harms. |

Responsible use means considering how AI affects people. Core ideas: fairness, privacy and data protection, transparency, accountability (people and organisations stay responsible), safety and reliability, and human oversight (meaningful review for important decisions about health, education, work, money, legal rights, or safety). When using generative AI: be specific; give context; verify important claims; protect confidential information; disclose AI use when required; keep responsibility for what you submit or decide; and respect intellectual property.

#### ACTIVITY 1.6 Risk Radar

*Pairs • 10 minutes*

| | |
|---|---|
| **Goal** | Name the type of risk in a realistic situation and suggest a sensible safeguard. |
| **Preparation** | Risk labels: Inaccurate results • Bias • Privacy • Lack of transparency • Overreliance • Security / misuse. |
| **Task** | For each case, choose the best risk label and write one practical safeguard.<br><br>1. A chatbot gives a convincing reference to a research paper that does not exist.<br>2. A hiring model trained on past decisions rejects more applicants from a group that was previously under-represented.<br>3. A student pastes a classmate's feedback, with the classmate's name and ID, into a public AI tool.<br>4. A bank refuses a loan, and nobody can explain how the model reached its decision.<br>5. A student submits an AI answer without reading it, and it contains an error.<br>6. Someone clones a manager's voice to ask for an urgent payment. |
| **Observation** | Note any case that could fit two labels, and say which label you chose and why. |
| **Reflection** | Which risk worries you most for your own study or work, and what one habit would reduce it? |
| **Feedback (try first, then check)** | See table below. |

| Case | Risk | Example safeguard |
|---:|---|---|
| 1 | Inaccurate results (fabrication) | Check that the source exists and supports the claim. |
| 2 | Bias | Test performance across groups; add qualified human review; allow appeal. |
| 3 | Privacy | Do not share; remove identifiers; get permission; use approved tools. |
| 4 | Lack of transparency | Require explanations and a review route for important decisions. |
| 5 | Overreliance | Read, verify, and edit before use; keep responsibility. |
| 6 | Security/misuse | Verify through a second, trusted channel before acting. |

### 1.7 Apply to Glitch: Interrogate the Witness

**APPLY** — *Check an AI answer instead of trusting it*

#### ACTIVITY 1.7 Interrogate Glitch

*Individual or pairs • 20 minutes • optional chatbot; fallback sample included*

| | |
|---|---|
| **Goal** | Practise treating AI output as information to evaluate, using evidence rather than confidence. |
| **Preparation** | **Option A (live):** an AI chatbot that your course allows. Do not enter personal information.<br>**Option B (fallback, no chatbot needed):** use Glitch's sample answer below. It is a fictional example written for this guide (not a real AI log), and it contains deliberate mistakes. |
| **Prompt** | Tell me three facts about the history of AI. |
| **Glitch's sample answer** | 1) Alan Turing proposed the Turing Test in 1950. 2) The Dartmouth research project in 1965 established AI as a research field. 3) Deep learning was invented in the 2020s and made rule-based systems obsolete. |
| **Task** | **Option B:** Mark each of Glitch's three "facts" as correct, incorrect, or overstated. Use the timeline in Activity 1.4 as your evidence source, and say what extra source you would check. **Option A:** Ask a chatbot "What is the difference between rule-based software and machine learning?" twice, and compare the two answers. List one claim you would verify, then check it against this guide or a reliable source.<br><br>Rewrite the prompt to be better: name the audience, length, and format, and ask for uncertainty to be flagged (for example: "Explain AI to a beginner in about 150 words with two everyday examples and one limitation"). |
| **Observation** | Record each claim, your verdict, your evidence, and (Option A) any difference between the two chatbot answers. |
| **Reflection** | Would an AI answer like this be enough as an academic reference? Why or why not? What did the confident tone tell you about accuracy? |
| **Feedback (try first, then check)** | **Option B answer.** (1) Correct: Turing published in 1950. (2) Incorrect: the Dartmouth project was in 1956. (3) Incorrect and overstated: deep learning achieved major progress in the 2010s, and rule-based approaches are still used, so they are not "obsolete."<br><br>**Learning point.** Fluent, confident answers can still be wrong. AI output should be treated as information to evaluate, not fact. For an academic claim, you need credible research or official guidance, the sources, and a citation you have checked. A more specific prompt gives a better chance of a useful answer, but it still needs checking. |

---

# Topic 2: Machine Learning Basics

## 2.1 What Is Machine Learning?

Machine Learning (ML) is an approach to AI in which a computer system learns patterns from data and uses those patterns to make predictions or decisions.

Instead of manually programming every possible rule, developers train a model using examples relevant to a task.

For instance, a spam filter can be trained using emails labeled as spam or not spam. After training, the model can estimate whether a new email belongs to either category.

## 2.2 Important Machine Learning Terms

- **Data:** Information used to develop, train, or evaluate a model.
- **Feature:** An input characteristic used by a model, such as an email's length or the number of links it contains.
- **Label:** The known answer associated with an example in a labeled dataset.
- **Algorithm:** A procedure or set of methods used to learn patterns or process information.
- **Model:** The learned system produced through a training process.
- **Training:** The process through which a model learns patterns from data.
- **Prediction:** An estimate or output produced by a trained model.
- **Evaluation:** The process of checking how well a model performs on relevant data.

## 2.3 The Basic Machine Learning Process

A simplified machine learning workflow includes:

1. **Define the problem.** Decide what the system should predict or identify.
2. **Collect data.** Gather information relevant to the problem.
3. **Prepare the data.** Check its quality, handle missing or inconsistent information, and organize it appropriately.
4. **Train the model.** Use a suitable method to learn patterns from the training data.
5. **Evaluate the model.** Test its performance using data that was not used to fit the model.
6. **Use and monitor the model.** Examine its predictions and check whether its performance remains suitable over time.

A model's quality depends partly on the quality and suitability of its data, its design, and the way it is evaluated.

## 2.4 Three Common Types of Machine Learning

### A. Supervised Learning

Supervised learning uses labeled training examples.

**Example:** A model learns from photographs labeled "cat" or "dog" and then predicts which category best fits a new photograph.

Two common supervised learning tasks are:

- **Classification:** Predicting a category, such as whether an email is spam.
- **Regression:** Predicting a numerical value, such as the expected price of a house.

### B. Unsupervised Learning

Unsupervised learning identifies patterns or structures in data without relying on supplied target labels for the learning task.

**Example:** A business groups customers according to similarities in their purchasing behavior.

The groups discovered by the model still need to be interpreted carefully; they do not automatically represent meaningful or accurate categories.

### C. Reinforcement Learning

Reinforcement learning involves an agent learning how to choose actions through interaction with an environment and feedback in the form of rewards or penalties.

**Example:** An agent learns to play a game by receiving rewards for successful actions and improving its strategy through repeated attempts.

## 2.5 Understanding Overfitting

Overfitting occurs when a model fits its training data too closely and performs poorly on new, unseen examples.

Imagine a student who memorizes answers to a few practice questions but cannot solve a new question that tests the same concept differently.

The student has memorized examples instead of developing a more general understanding. Overfitting is a similar problem for machine learning models.

Testing with suitable unseen data helps identify whether a model generalizes beyond its training examples.

## Key Points to Remember

- Machine learning uses data to learn patterns.
- Training produces a model that can make predictions or decisions.
- Supervised learning uses labeled examples.
- Unsupervised learning looks for patterns without supplied target labels.
- Reinforcement learning uses feedback from actions.
- A model that performs well on training data may still perform poorly on new data.

## Review Questions

1. What is the difference between data, an algorithm, and a model?
2. What is the difference between training and evaluation?
3. Explain the difference between supervised, unsupervised, and reinforcement learning.
4. Give one example of a classification task and one example of a regression task.
5. What is overfitting, and why is it a problem?

## Learning Activity

Classify each scenario as supervised learning, unsupervised learning, or reinforcement learning.

1. A model learns from emails labeled "spam" and "not spam."
2. A system groups news articles according to similarities in their content without predefined topic labels.
3. An agent learns to play a game by receiving rewards for successful actions.

For each answer, explain which feature of the scenario supports your classification.

---

# Topic 3: Generative AI and Large Language Models

## 3.1 What Is Generative AI?

Generative AI refers to AI systems designed to generate new content based on patterns learned from training data.

Depending on the system, generated content may include:

- Text and summaries.
- Images and illustrations.
- Audio and music.
- Video.
- Computer code.

Generative AI can support brainstorming, drafting, translation, explanation, and creative exploration. However, generated content may contain errors, bias, or material that requires further review.

## 3.2 What Is a Large Language Model?

A Large Language Model (LLM) is an AI model designed to process and generate language.

Many LLMs generate text by predicting likely next tokens based on the preceding context. A token may be a word, part of a word, or another unit of text.

This process allows an LLM to produce responses that can resemble human writing. However, fluent language does not guarantee factual accuracy, genuine understanding, or reliable reasoning.

## 3.3 Understanding Prompts

A **prompt** is the instruction, question, or information provided to an AI tool.

A useful prompt often includes:

- **Goal:** What you want the tool to do.
- **Context:** Information needed to understand the task.
- **Constraints:** Requirements or limits the response should follow.
- **Format:** How the response should be presented.

### Example of Improving a Prompt

**Vague prompt:**

"Explain machine learning."

**Improved prompt:**

"Explain machine learning to a beginner in approximately 150 words. Describe the basic training process and give one everyday example. Use simple language and identify one important limitation."

The improved prompt specifies the audience, length, content, example, style, and limitation.

A more detailed prompt can improve relevance, but it does not guarantee that the response will be correct.

## 3.4 AI Hallucinations and Other Limitations

An AI hallucination is an output that presents false, fabricated, or unsupported information as though it were true.

For example, an AI tool might invent a research paper, give an incorrect date, or describe a nonexistent feature of a product.

Other limitations may include:

- Outdated information.
- Missing context.
- Incomplete explanations.
- Biased assumptions.
- Incorrect calculations.
- Misinterpretation of instructions.
- References that do not exist or do not support the claims being made.

AI-generated information should therefore be checked, especially when it affects academic work, finances, health, safety, or important decisions.

## Key Points to Remember

- Generative AI produces content based on learned patterns.
- LLMs specialize in processing and generating language.
- A prompt guides an AI system but does not guarantee a correct answer.
- A confident, fluent response may still be wrong.
- Important facts and references should be verified independently.

## Review Questions

1. What is generative AI?
2. What is an LLM, and what kinds of tasks can it support?
3. What information can make a prompt more useful?
4. What is an AI hallucination?
5. Why should an AI-generated reference be checked before it is cited?

## Learning Activity

Ask an AI tool to explain a topic you are studying. Then:

1. Write down the prompt you used.
2. Identify two factual claims in the response.
3. Check those claims against reliable sources.
4. Record any errors, unsupported claims, or missing context.
5. Rewrite your prompt to improve the response.

Follow your instructor's rules when using AI tools for coursework.

---

# Topic 4: Real-World Applications of AI

## 4.1 AI in Education

AI can help learners explore difficult concepts, generate practice questions, receive language feedback, and organize study materials.

**Potential benefits:**
- Additional explanations and examples.
- Practice opportunities.
- Support for some learning needs.

**Potential limitations:**
- Incorrect explanations.
- Overdependence on AI-generated answers.
- Privacy concerns involving student information.
- Academic integrity issues when AI use violates course rules.

AI should support learning rather than replace independent thought and effort.

## 4.2 AI in Healthcare

AI systems can assist healthcare professionals with tasks such as analyzing medical images, identifying patterns in data, and supporting some administrative activities.

**Potential benefits:**
- Assistance with reviewing large amounts of information.
- Support for identifying patterns.
- Possible improvements in workflow efficiency.

**Potential limitations:**
- Incorrect predictions.
- Bias or gaps in the data.
- Privacy and security risks.
- The need for qualified professional judgment and appropriate oversight.

An AI output should not be treated as a substitute for qualified medical advice.

## 4.3 AI in Business and Finance

Businesses may use AI to forecast demand, analyze customer behavior, detect unusual transactions, and automate certain repetitive tasks.

**Potential benefits:**
- Faster analysis of large datasets.
- Support for planning and decision-making.
- Automation of suitable repetitive tasks.

**Potential limitations:**
- Inaccurate forecasts.
- Unfair outcomes caused by biased data or system design.
- Privacy risks.
- Financial losses when predictions are unreliable.

## 4.4 AI in Transportation

AI can support route planning, traffic analysis, driver-assistance features, and systems that identify objects around vehicles.

**Potential benefits:**
- Assistance with navigation.
- Analysis of traffic patterns.
- Support for selected safety-related tasks.

**Potential limitations:**
- Errors in unusual or difficult conditions.
- Dependence on the quality of sensors and data.
- Safety risks if systems are used beyond their capabilities.

## 4.5 AI in Digital Services and Entertainment

AI may recommend videos, music, products, or articles based on user activity and preferences.

**Potential benefits:**
- Personalized recommendations.
- Faster discovery of relevant content.
- Improved convenience.

**Potential limitations:**
- Privacy concerns.
- Repetitive recommendations.
- Reduced exposure to different viewpoints or interests.
- Recommendations that reflect commercial or design priorities rather than a user's broader needs.

## Evaluating an AI Application

When examining any AI application, ask:

1. What problem is the system intended to solve?
2. Who benefits from its use?
3. What information does it need?
4. What could happen if it makes a mistake?
5. Could it disadvantage certain people or groups?
6. How will a person check its output or correct an error?

## Key Points to Remember

- AI can support many industries, but its usefulness depends on the task and context.
- Benefits should be considered alongside risks and limitations.
- High-impact applications require suitable safeguards and human oversight.
- An AI system should be evaluated according to its actual performance, not just its advertised capabilities.

## Review Questions

1. Identify two industries that use AI.
2. Describe one benefit and one limitation of AI in education.
3. Why is human oversight important in healthcare applications?
4. How might an AI recommendation system affect the content a user sees?
5. What questions should be asked before adopting an AI system?

## Learning Activity

Choose one real-world AI application. Prepare a short evaluation that identifies:

- The problem it addresses.
- Its intended users.
- One potential benefit.
- One potential risk.
- A method for checking its performance.
- A safeguard that could reduce harm.

Support factual claims about a specific product or system with reliable sources.

---

# Topic 5: Responsible AI, Ethics, and Privacy

## 5.1 What Is Responsible AI?

Responsible AI involves developing, selecting, and using AI systems with attention to safety, fairness, privacy, accuracy, transparency, and their effects on people.

An AI system can be technically impressive and still be unsuitable for a particular use. Responsible use requires considering both the system's capabilities and the consequences of its outputs.

## 5.2 Accuracy and Reliability

AI systems can produce incorrect, incomplete, misleading, or outdated information.

**Responsible practice:** Verify important claims against suitable sources, check calculations and references, and avoid treating AI output as the only basis for consequential decisions.

The appropriate level of checking depends on the importance and risk of the task.

## 5.3 Bias and Fairness

Bias may arise from training data, data collection methods, system design, evaluation choices, or the context in which a system is used.

For example, a hiring model trained on historical decisions may reproduce unfair patterns found in those decisions.

**Responsible practice:** Examine whether a system performs differently across relevant groups, use appropriate evaluation methods, and investigate unfair outcomes rather than assuming the model is neutral.

Fairness is context-dependent and may require careful consideration of competing goals.

## 5.4 Privacy and Data Protection

AI tools may process information provided by users, including personal or confidential data.

**Responsible practices:**
- Avoid entering passwords, private credentials, or unnecessary sensitive information.
- Follow applicable organizational, school, and legal requirements.
- Check how a tool handles and retains submitted information.
- Obtain appropriate permission before sharing other people's information.

Only provide information that is necessary and authorized for the task.

## 5.5 Transparency and Accountability

**Transparency** means providing appropriate information about how AI is being used and communicating relevant limitations.

**Accountability** means that people and organizations remain responsible for decisions and actions involving AI.

Using an AI tool does not remove responsibility for checking its output or considering the consequences of using it.

## 5.6 Human Oversight

Human oversight means that people review, supervise, or intervene in AI-supported processes when appropriate.

The level of oversight should reflect the possible consequences of an error. A low-risk brainstorming task may require less review than a decision that could affect someone's health, education, employment, finances, or safety.

## 5.7 Academic Integrity

Students should follow their institution's and instructor's rules regarding AI assistance.

Responsible academic use may include:
- Asking for explanations of difficult concepts.
- Generating practice questions for revision.
- Receiving feedback on writing when permitted.
- Checking ideas against course materials.
- Disclosing AI assistance when required.

Students should not present AI-generated work as their own when doing so violates course rules. They remain responsible for the accuracy, originality, and integrity of submitted work.

## Key Points to Remember

- AI outputs should be checked for accuracy.
- Bias can lead to unfair outcomes.
- Personal and confidential information must be handled carefully.
- People and organizations remain accountable for AI-supported decisions.
- Human oversight should reflect the risks of the task.
- Academic AI use must follow course requirements.

## Review Questions

1. What is responsible AI?
2. Give an example of how bias can affect an AI system.
3. Why should users be careful about entering personal information into AI tools?
4. Explain the difference between transparency and accountability.
5. Why might a high-impact AI application require stronger human oversight?
6. Give two examples of responsible AI use in education.

## Learning Activity

Read the scenario:

A student asks an AI tool to produce a report containing statistics and research references. The student submits the report without checking whether the statistics are correct or whether the references exist.

Answer the following:

1. Identify two risks in the student's approach.
2. Explain how the student could verify the information.
3. Describe how the student should check the course rules on AI assistance.
4. Explain who is responsible for the accuracy of the submitted work.

---

# Topic 6: Practical AI Skills and Critical Evaluation

## 6.1 Writing Effective Prompts

A prompt should clearly communicate the task and provide enough information for the AI tool to respond appropriately.

A useful prompt can include:

- **Goal:** State the task.
- **Context:** Explain the situation or background.
- **Audience:** Identify who the response is for.
- **Constraints:** Set relevant limits or requirements.
- **Output format:** Specify whether you want a list, table, explanation, or another format.
- **Quality criteria:** Explain what a useful response should include.

### Prompt Improvement Example

**Weak prompt:**

"Tell me about AI."

**Improved prompt:**

"Explain Artificial Intelligence to a beginner in simple English. Distinguish AI from machine learning, provide two everyday examples, and identify one limitation. Organize the response with headings and keep it under 200 words."

The improved version gives the tool a clearer goal and a more specific output format.

## 6.2 Improve Prompts Iteratively

Prompting often works best as an iterative process:

1. Write an initial prompt.
2. Review the response.
3. Identify what is missing or unclear.
4. Add relevant context or constraints.
5. Request a revised response.
6. Check the revised response independently.

A more detailed prompt may improve relevance and structure, but it does not remove the need for verification.

## 6.3 Evaluating AI-Generated Answers

Use the following checks when reviewing an AI response.

### Accuracy

Are the claims correct? Verify important facts using reliable sources.

### Relevance

Does the response answer the question, or does it include unrelated information?

### Completeness

Does it address every important part of the task? Are important qualifications or limitations missing?

### Evidence

Are references real, credible, relevant, and supportive of the claims they are used to justify?

### Bias

Does the response make unfair assumptions, overlook certain perspectives, or treat people or groups differently without a suitable reason?

### Clarity

Is the explanation understandable and logically organized? Remember that clear writing is not proof of accuracy.

### Currency

Could the information have changed? For time-sensitive topics, check current and authoritative sources.

## 6.4 Using Reliable Sources

When checking a factual claim:

1. Identify the specific claim that needs verification.
2. Find a suitable source, such as an official publication, relevant textbook, peer-reviewed research paper, or reputable institution.
3. Check the author's or organization's expertise and the source's publication date.
4. Confirm that the source actually supports the claim.
5. Compare important claims against additional independent sources when appropriate.
6. Record the sources used and cite them according to your assignment requirements.

Do not assume that a reference is genuine simply because an AI tool provides a title, author, link, or publication date.

## 6.5 Reflecting on AI Use

After completing an AI-assisted task, consider:

- What did the tool help me accomplish?
- Which parts of its response were useful?
- What errors or limitations did I identify?
- Which claims did I verify independently?
- Did I protect private information?
- Did I follow the relevant rules?
- What would I do differently next time?

This reflection helps users improve their judgment rather than simply relying on AI-generated answers.

## Key Points to Remember

- Effective prompts provide clear goals, context, and constraints.
- Prompts can be refined through repeated review.
- AI responses should be evaluated for accuracy, relevance, completeness, evidence, bias, clarity, and currency.
- Important claims should be verified using suitable sources.
- Responsible AI use includes privacy protection, academic integrity, and independent judgment.

## Review Questions

1. What information can make a prompt more effective?
2. Why might you need to revise a prompt after receiving an initial answer?
3. Name four checks you can use to evaluate an AI-generated response.
4. How can you verify whether an AI-generated reference supports a claim?
5. Why is a clear and confident response not necessarily a reliable response?
6. What should you reflect on after completing an AI-assisted task?

## Learning Activity

Complete a small learning task with an AI tool, following your instructor's rules.

1. Write a prompt with a clear goal, context, and output format.
2. Review the response for accuracy, relevance, and completeness.
3. Select two factual claims and verify them using reliable sources.
4. Identify one limitation or uncertainty in the response.
5. Improve the prompt and compare the revised response with the original.
6. Write a short reflection describing what you learned and what you verified.

---

# 3. Quick Comparison Tables

## Machine Learning Approaches

| Approach | Type of learning signal | Example |
|---|---|---|
| Supervised learning | Labeled training examples | Classifying emails as spam or not spam |
| Unsupervised learning | Patterns in data without supplied target labels | Grouping customers by purchasing behavior |
| Reinforcement learning | Feedback through rewards or penalties | Learning a strategy for a game |

## Classification and Regression

| Task | Typical output | Example |
|---|---|---|
| Classification | A category or class | Predicting whether an email is spam |
| Regression | A numerical value | Estimating a house's sale price |

## Responsible AI Practices

| Concern | Example of a risk | Responsible practice |
|---|---|---|
| Accuracy | An AI tool invents a fact | Verify important claims |
| Bias and fairness | A model disadvantages a group | Evaluate outcomes and investigate disparities |
| Privacy | A user shares confidential information | Minimize data sharing and follow applicable rules |
| Transparency | AI assistance is concealed when disclosure is required | Follow disclosure requirements |
| Accountability | A person accepts an AI recommendation without review | Maintain appropriate human responsibility and oversight |
| Academic integrity | A student submits prohibited AI-generated work | Follow the instructor's rules and complete work honestly |

---

# 4. Key Terms Glossary

| Term | Definition |
|---|---|
| Artificial Intelligence (AI) | A field focused on systems that perform tasks associated with intelligent behavior |
| Algorithm | A procedure or method for processing information or learning patterns |
| Machine Learning (ML) | An approach in AI that learns patterns from data |
| Deep Learning (DL) | Machine learning that uses neural networks with multiple processing layers |
| Data | Information used to develop, train, or evaluate a system |
| Feature | An input characteristic used by a model |
| Label | A known target or answer associated with a training example |
| Model | A learned system that produces predictions or other outputs |
| Training | The process of learning patterns from data |
| Prediction | An estimate or output produced by a model |
| Classification | Predicting a category |
| Regression | Predicting a numerical value |
| Overfitting | Fitting training data too closely and performing poorly on new examples |
| Generative AI | AI designed to generate new content |
| Large Language Model (LLM) | An AI model designed to process and generate language |
| Prompt | An instruction or input provided to an AI tool |
| Hallucination | False, fabricated, or unsupported content presented as though it were true |
| Bias | A systematic tendency that may contribute to unfair or distorted outcomes |
| Privacy | The protection and appropriate handling of personal information |
| Human oversight | Human review or supervision of an AI system or its outputs |
| Verification | Checking a claim against suitable evidence or sources |

---

# 5. Revision Plan

Use this sequence to revise the module.

### Step 1: Review the Concepts

Read the six topics in order. Identify unfamiliar terms and write a brief definition for each in your own words.

### Step 2: Practise Active Recall

Close the study guide and answer the review questions without looking at the notes.

Active recall helps you identify what you understand and what you need to revise.

### Step 3: Apply the Concepts

Complete the learning activities. Use your own examples and explain why your answers are appropriate.

### Step 4: Check Your Understanding

Compare your answers with the relevant chapter materials. Correct misunderstandings and revisit difficult concepts.

### Step 5: Complete the Practice Question Bank

Work through `test-bank/practice-questions.md` without immediately checking the answers.

Review any incorrect answers and explain why the correct option is better.

### Step 6: Practise Verification

Choose a factual claim from an AI-generated response and check it against reliable sources. Confirm that the source exists and supports the claim.

### Step 7: Review Before Submission

Make sure you can explain the main concepts in your own words and apply them to new examples.

---

# 6. Final Self-Assessment Checklist

Before completing the module, check whether you can:

- [ ] Define AI and explain how it differs from rule-based automation.
- [ ] Explain the relationship between AI, machine learning, and deep learning.
- [ ] Describe data, features, labels, training, models, and predictions.
- [ ] Distinguish supervised, unsupervised, and reinforcement learning.
- [ ] Explain the difference between classification and regression.
- [ ] Describe overfitting and why testing on unseen data matters.
- [ ] Explain generative AI and the basic purpose of LLMs.
- [ ] Identify hallucinations and other limitations of AI-generated content.
- [ ] Evaluate the benefits and risks of an AI application.
- [ ] Recognize concerns involving accuracy, bias, privacy, and fairness.
- [ ] Explain why human oversight and accountability matter.
- [ ] Write a prompt with a clear goal, context, and output format.
- [ ] Verify important AI-generated claims using reliable sources.
- [ ] Follow academic integrity and AI-use requirements.
- [ ] Reflect critically on the usefulness and limitations of AI tools.

If you cannot confidently check an item, revisit the relevant topic and practise explaining it in your own words.

---

## 7. Important Note

This study guide is a revision resource for the Curious Mind AI Overview module. It should be used alongside the module chapters, practice questions, and any instructions provided by the course instructor.

Before final submission, check that the guide matches the assignment requirements, that examples and factual claims are reviewed, and that any required references or citations are included.
