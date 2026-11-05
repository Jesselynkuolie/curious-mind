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

**Learning-experience identity:** Every chapter is a "Case" solved by Detective Pip and the Agency's overconfident robot, Glitch. All six Cases use the same labels, boxes, and activity cards.

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
> 
> I'm Detective Pip. My job is to ask good questions: What is the evidence? What happens if I change one thing? Could this be wrong? I will guide you through each Case.

> **GLITCH THE OVERCONFIDENT BOT SAYS**
> 
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
> 
> Everything with a chip is AI! My calculator is AI! My toaster is AI! And my spam filter is definitely AI — although I cannot explain how it works. Also, I am never wrong.

> **DETECTIVE PIP SAYS**
> 
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
> 
> Important distinction: traditional rule-based software is not automatically AI, but AI is a broad field that includes rules, search, reasoning, machine learning, and more. So it would be wrong to say that every AI system learns from data. (Remember card 9?)

**Worked example (school support).** Approach A: the school writes the rule "if an exam score is below 50, flag the student." The program checks the score and reports. Approach B: the school trains a model on past student data to estimate who may need support. The model's prediction is not guaranteed to be correct, so the school must evaluate it and must not treat it as a final judgement about a student.

**Quick check.** In your own words, what is AI? Give one AI system you have encountered. Then answer: why might a school prefer human judgement alongside an AI prediction instead of letting the model decide alone? *(Model answer: predictions can be wrong or biased, students' circumstances are not fully captured in data, and a teacher can take context and fairness into account.)*

### 1.3 Try and Observe: The Spam Detective Lab

**TRY / OBSERVE** — *Rules versus learning, with real evidence*

> **DETECTIVE PIP SAYS**
> 
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
| **Task** | For each case, choose the best risk label and write one practical safeguard.<br><br>1. A chatbot gives a convincing reference to a research paper that does not exist.<br>2. A hiring model trained on past decisions rejects more applicants from a group that was previously underrepresented.<br>3. A student pastes a classmate's feedback, with the classmate's name and ID, into a public AI tool.<br>4. A bank refuses a loan, and nobody can explain how the model reached its decision.<br>5. A student submits an AI answer without reading it, and it contains an error.<br>6. Someone clones a manager's voice to ask for an urgent payment. |
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
| **Preparation** | **Option A (live):** an AI chatbot that your course allows. Do not enter personal information.<br>**Option B (fallback, no chatbot needed):** use Glitch's sample answer below. This is a fictional example written for this guide (not a real AI log) and contains deliberate mistakes. |
| **Prompt** | Tell me three facts about the history of AI. |
| **Glitch's sample answer** | 1) Alan Turing proposed the Turing Test in 1950. 2) The Dartmouth research project in 1965 established AI as a research field. 3) Deep learning was invented in the 2020s and made rule-based systems obsolete. |
| **Task** | **Option B:** Mark each of Glitch's three "facts" as correct, incorrect, or overstated. Use the timeline in Activity 1.4 as your evidence source, and say what extra source you would check. **Option A:** Ask a chatbot "What is the difference between rule-based software and machine learning?" twice, and compare the two answers. List one claim you would verify, then check it against this guide or a reliable source.<br><br>Rewrite the prompt to be better: name the audience, length, and format, and ask for uncertainty to be flagged (for example: "Explain AI to a beginner in about 150 words with two everyday examples and one limitation"). |
| **Observation** | Record each claim, your verdict, your evidence, and (Option A) any difference between the two chatbot answers. |
| **Reflection** | Would an AI answer like this be enough as an academic reference? Why or why not? What did the confident tone tell you about accuracy? |
| **Feedback (try first, then check)** | **Option B answer.** (1) Correct: Turing published in 1950. (2) Incorrect: the Dartmouth project was in 1956. (3) Incorrect and overstated: deep learning achieved major progress in the 2010s, and rule-based approaches are still used, so they are not "obsolete."<br><br>**Learning point.** Fluent, confident answers can still be wrong. AI output should be treated as information to evaluate, not fact. For an academic claim, you need credible research or official guidance, the sources, and a citation you have checked. A more specific prompt gives a better chance of a useful answer, but it still needs checking. |

### 1.8 Check Your Understanding

**CHECK** — *Six quick questions before you move on*

| # | Question | Answer and explanation |
|---:|---|---|
| 1 | Which statement describes AI best: (A) technology only for robots; (B) a field of computing about systems that perform tasks associated with intelligent behaviour; (C) a method of storing files; (D) a system that is always correct? | B. AI is a broad field, not just robots, and it is not always correct. |
| 2 | Complete: deep learning is a subset of ____, which is a subset of ____. | Machine learning; AI. |
| 3 | True or false: a pass/fail program with a 50-mark threshold is machine learning. | False. It follows an explicit rule. |
| 4 | Name two benefits and two limitations of AI. | Benefits: efficiency, pattern recognition, personalisation, accessibility, decision support. Limitations: inaccurate results, bias, privacy risk, lack of transparency, overreliance, misuse. |
| 5 | Why is a high score on training emails not enough to trust a spam model? | It may have learned the training examples too closely. You need performance on unseen examples. |
| 6 | Name two practices for responsible generative-AI use. | Verify important claims; protect confidential information; disclose AI use when required; keep responsibility; respect intellectual property. |

### 1.9 Case Notes (Summary)

- AI is a field of computing for systems that perform tasks associated with intelligent behaviour. Intelligent-looking is not the same as understanding.
- Machine learning is a subset of AI and deep learning is a subset of machine learning. Not every AI system learns from data.
- Rule-based software follows explicit instructions; learning systems find patterns in data. Learned systems must be tested on unseen examples.
- AI is used in education, healthcare, transport, business, and online services, with real benefits and real risks: inaccuracy, bias, privacy, lack of transparency, overreliance, and misuse.
- Responsible use needs fairness, privacy, transparency, accountability, reliability, and human oversight. AI is a valuable tool whose outputs must be understood and evaluated.

> **RESOURCE — Elements of AI — Chapter 1, "What is AI?" (University of Helsinki and MinnaLearn)**
> **What is it?** Free online introductory AI course; the first chapter discusses how AI can be defined and why the definition is debated. Link: https://www.elementsofai.com
>
> **Why use it?** Gives a second explanation of the question Case 1 asks: what counts as AI, and why the boundary is fuzzy?
>
> **Which part matters?** Chapter 1 only (about 30–45 minutes). [Team to confirm the exact section range after reading it.]
>
> **What should I do?** Before reading, write your own one-sentence definition of AI. After reading, compare it and note one idea you would add or change.
>
> **Watch out for** The course may ask you to create an account to save progress. It is a general introduction, so terminology may differ slightly from this guide.
>
> **If I cannot access it** Use the IBM overview https://www.ibm.com/think/topics/artificial-intelligence (note that it is a company page and can emphasise its own products) or re-read Section 1.2.

---

## Case 2 • The Fraud Alarm

**Module Chapter 2: Machine Learning Basics • Prerequisite: Case 1**

> **GLITCH THE OVERCONFIDENT BOT SAYS**
> My fraud detector is 95% accurate! That is practically perfect. Give me a medal.

> **DETECTIVE PIP SAYS**
> **The mystery:** a bank's history shows 95 of every 100 transactions are legitimate. Is a 95%-accurate fraud detector really good? We will find out by building a scoreboard, training a small classifier, and breaking a neural network on purpose.

### Case map

| Item | Details |
|---|---|
| **Learning objectives** | 1. Define machine learning and its relationship to AI. 2. Describe data, features, labels, and models. 3. Distinguish supervised, unsupervised, and reinforcement learning. 4. Explain classification versus regression. 5. Describe the stages of training and evaluating a model. 6. Explain overfitting and why unseen test data is needed. 7. Explain how data quality and bias affect results. |
| **Time** | About 1.5 hours (the original reading is 40–50 minutes). |
| **Sequence** | 2.1 Predict (scoreboard) → 2.2 Explain (core ideas) → 2.3 Try (text classifier) → 2.4 Try (TensorFlow Playground) → 2.5 Check |

### 2.1 Encounter and Predict: Is 95% Accuracy Good?

**ENCOUNTER + PREDICT** — *Three fraud alarms, one scoreboard*

#### ACTIVITY 2.1 The Fraud Alarm Scoreboard

*Individual or pairs • 20 minutes • pencil, paper, calculator*

| | |
|---|---|
| **Goal** | Compute accuracy, precision, and recall and discover why accuracy alone can mislead. |
| **Preparation** | A bank tests three alarm models on 100 transactions: 95 are legitimate and 5 are fraud. "Positive" means "flagged as fraud". |
| **Model table** | See below. |
| **Formulas** | **Accuracy** = (TP + TN) ÷ total • **Precision** = TP ÷ (TP + FP) • **Recall** = TP ÷ (TP + FN). |
| **Task** | **PREDICT:** before calculating, which model do you think is best for the bank? Write it down with one reason.<br><br>Calculate accuracy, precision, and recall for A, B, and C (if you divide by zero, write "undefined: no positive predictions").<br><br>Choose a model for each situation and justify it: (i) a bank where every missed fraud is very costly and flagged transactions are reviewed by staff; (ii) a bank whose customers get angry when legitimate purchases are blocked. |
| **Observation** | Complete a table with accuracy, precision, and recall for each model. Circle the model you predicted and its real scores. |
| **Reflection** | Why does Model A score 95% accuracy while catching no fraud? What question does each metric answer? |
| **Feedback (try first, then check)** | See feedback table below. |

**Model table**

| Model | What it does | Fraud caught (TP) | Legit wrongly flagged (FP) | Fraud missed (FN) | Legit correctly passed (TN) |
|---|---|---:|---:|---:|---:|
| A | Always says "legitimate" | 0 | 0 | 5 | 95 |
| B | Flags 10 transactions | 4 | 6 | 1 | 89 |
| C | Flags 20 transactions | 5 | 15 | 0 | 80 |

**Feedback table**

| Model | Accuracy | Precision | Recall |
|---|---:|---:|---:|
| A | 95% | undefined (0 flagged) | 0% |
| B | 93% | 40% (4 of 10) | 80% (4 of 5) |
| C | 85% | 25% (5 of 20) | 100% (5 of 5) |

**Interpretation.** Model A has the highest accuracy and is useless for detecting fraud. Precision answers "Of the flagged transactions, how many were fraud?" Recall answers "Of all fraud, how many did we catch?" In situation (i), C (or B) may be preferred because recall matters and humans can review false alarms; in (ii), a model with higher precision, such as B, may be preferred. **The right balance depends on the cost of each kind of error.** Alternative justifications are valid if they use these numbers.

### 2.2 Explain: How Machines Learn

**EXPLAIN** — *From the scoreboard to the whole pipeline*

**Machine learning (ML)** is an area of AI in which computer systems use data to learn patterns and perform tasks without every decision being written as a separate rule. In the Spam Detective Lab, the word scores were learned from labelled examples instead of typed in by a programmer.

| Term | Meaning | Example |
|---|---|---|
| Data/dataset | Information used to develop or operate a system; an organised collection of it. | Thousands of labelled emails |
| Feature | An input characteristic used by a model. | Number of links in an email |
| Label | The known target in supervised learning. | "Spam" or "Not spam" |
| Algorithm | A procedure used to learn patterns or solve a problem. | A procedure that learns to classify emails |
| Model | A learned representation of patterns used for predictions. | A trained email classifier |
| Training | Using data to adjust a model's parameters. | Learning from labelled emails |
| Prediction | Model output for a new input. | Classifying a new email as likely spam |
| Evaluation | Measuring performance on relevant data. | Checking how often the classifier is correct |

**The ML pipeline:** Define the problem → Collect data → Prepare data (fix duplicates, missing values, errors) → Select a learning method → Train → Evaluate on data not used for training → Deploy and monitor. The cycle may repeat if results are poor.

**Three types of machine learning**

| Type | Data or feedback | Purpose | Example |
|---|---|---|---|
| Supervised | Examples with known labels or values | Predict a category or value | Classifying emails |
| Unsupervised | Data without predefined target labels | Find patterns or groupings | Grouping customers by purchases |
| Reinforcement | Rewards or penalties from actions in an environment | Learn a strategy by interaction | Learning to play a game |

**Classification** predicts a category (spam or not spam; cat, dog, or bird). **Regression** predicts a number (house price; travel time). Discovered groups in unsupervised learning are not automatically meaningful; people must interpret them.

**Training, validation, and test data**

To check that a model generalises, data is often split. Example for 1,000 labelled examples: 700 for training (fit the model), 150 for validation (compare settings during development), 150 for testing (final check). This is only an illustration. **Data leakage** happens when information that would not truly be available at prediction time influences training or evaluation, making results look unrealistically good.

**Overfitting, data quality, and bias**

**Overfitting:** a model fits its training data very closely, including noise or accidental patterns, and performs poorly on new data. Example: a dog classifier trained on photos where most dogs are on grass may learn "grass" instead of "dog". Ways to reduce it include more representative data, validation data, less unnecessary complexity, regularisation where appropriate, removing leakage, and testing in realistic conditions. None guarantees success.

**Data problems:** missing, incorrect, duplicate, unrepresentative, or outdated data. Bias can arise when data reflect past unfair practices (for example, historical hiring decisions). Reduce risk by checking data sources, checking representation, evaluating across groups, studying errors, protecting personal information, involving knowledgeable reviewers, and monitoring after deployment. Fairness cannot always be captured by one metric.

### 2.3 Try and Observe: Train a Small Text Classifier

#### ACTIVITY 2.2 Which Kind of Learning?

*Individual • 10 minutes*

| | |
|---|---|
| **Goal** | Classify real situations by learning type and task. |
| **Preparation** | None. |
| **Task** | For each scenario: (1) choose supervised, unsupervised, or reinforcement learning; (2) if supervised, choose classification or regression; (3) say what information you would need to evaluate it; (4) name one limitation.<br><br>**A** A system learns from emails labelled "Spam" / "Not spam" to classify new emails.<br>**B** A retailer wants groups of customers with similar buying patterns, without predefined groups.<br>**C** A model uses property features to estimate a house's selling price.<br>**D** An agent learns a strategy in a game from rewards and penalties.<br>**E** A model predicts whether a photo shows a cat, a dog, or a bird. |
| **Observation** | Write your answers in a small table with columns: scenario, learning type, task, evaluation data, limitation. |
| **Reflection** | Which scenario needs the most human oversight before its predictions are used for important decisions? Consider the consequences of errors and the people affected. |
| **Feedback (try first, then check)** | See table below. |

| Scenario | Type / task | Evaluation idea | Limitation example |
|---|---|---|---|
| A | Supervised • classification | Precision, recall, accuracy on separate test data | Legitimate emails flagged as spam |
| B | Unsupervised • clustering | Are groups meaningful, stable, useful? | Groups may not reflect real differences |
| C | Supervised • regression | Compare predicted and actual prices on test data | Market changes make old data outdated |
| D | Reinforcement learning | Test across many games or scenarios | May fail in situations unlike training |
| E | Supervised • classification | Test-set performance; study errors by image condition | Fails on images unlike the training data |

#### ACTIVITY 2.3 Spam or Not Spam: Train, Test, Break, Improve

*Pairs • 25 minutes • browser • Machine Learning for Kids*

> **RESOURCE — Machine Learning for Kids (Dale Lane) — text recognition project**
> **What is it?** A free web platform for training small machine learning models and using them in projects. Link: https://machinelearningforkids.co.uk
>
> **Why use it?** It makes the invisible training process visible: you provide labelled examples, press Train, and test the model yourself.
>
> **Which part matters?** The text-recognition project type only. Choose "Get started", then "Try it now" to use it without an account (your project cannot be saved, so keep notes). A free teacher account can be used for saved work.
>
> **What should I do?** Follow Activity 2.3. Do not type personal information into any example.
>
> **Watch out for** Small training sets give unstable results; this is a teaching tool, not a production system. The site's layout and messages may change; the team tested these steps on [date — insert] using [browser — insert].
>
> **If I cannot access it** Use the "illustrative results" table in the Feedback row of Activity 2.3 and answer its analysis questions.

| | |
|---|---|
| **Goal** | Experience supervised learning: labelled data → training → prediction → error analysis → better data. |
| **Preparation** | Open https://machinelearningforkids.co.uk → Get started → Try it now → Add a new project → name it SpamDetective, choose recognising text, language English → Create.<br><br>Training examples to type in (the site may ask for a minimum number per label): see table below. |
| **Task** | Open Train, add the two labels, and add all twelve examples. Open Learn & Test and choose Train new machine learning model. **PREDICT:** which of the six test messages below will the model get wrong?<br><br>Test each message and record the label and confidence the model gives:<br>(1) Free pizza at the student club tonight<br>(2) Congratulations, you won a vacation, click to claim<br>(3) Please verify your attendance for tomorrow's class<br>(4) Limited seats left for our study workshop<br>(5) Your parcel is waiting, pay a small fee to release it<br>(6) Meeting notes attached, call me when free.<br><br>**Improve:** for any message the model got wrong, add 3–5 new, different training examples in the correct label (for instance normal messages that contain "free", "verify", or "limited"), train again, and retest the same six messages. |
| **Observation** | Record a table: message • your prediction • model label • confidence • correct? (before). Repeat after retraining. Note which words appear in the mistakes. |
| **Reflection** | What patterns did the model learn from the words, and what did it not learn? Why did adding data change the result? Would testing only on your training messages have revealed the problem? Is the model "understanding" messages? What does your evidence suggest? |
| **Feedback (try first, then check)** | Expected outcomes vary with the platform version and the examples you typed, so use your own results. A common pattern is mistakes on messages that look spammy by single words (such as "free", "verify", "limited") but are normal in context (messages 1, 3, 4, 6), because the model learned word patterns rather than meaning. After adding varied normal examples, those mistakes often fall, showing that better, more representative training data improves a model.<br><br>**Fallback (hypothetical, not a real run):** Suppose a model labelled test messages as follows. Analyse it: (1) not_spam 55%; (2) spam 90%; (3) spam 70%; (4) spam 60%; (5) spam 52%; (6) not_spam 51%. Which results are probably wrong given human labels? (Answer: messages 3 and 4 are normal messages that the model wrongly calls spam; 1, 2, 5, and 6 agree with human labels, but the low confidence on 1, 5, and 6 shows the model is unsure.) Why might words like "verify" mislead it? (They appeared only in spam examples.)<br><br>Keep a screenshot of your before/after results for your own records. |

**Training examples**

| Label: spam | Label: not_spam |
|---|---|
| Win a free prize now | Can we move our meeting to 3 pm? |
| Claim your free gift card today | Here are the lecture notes from today |
| Urgent: verify your password to unlock your account | Don't forget the group project deadline on Friday |
| You have been selected for a cash reward | Thanks for your help with the assignment |
| Click here for a limited-time offer | Are you free for lunch tomorrow? |
| Cheap watches best price buy now | The library closes early on Saturday |

### 2.4 Try and Observe: Overfitting in TensorFlow Playground

> **RESOURCE — TensorFlow Playground (Google / TensorFlow team)**
> **What is it?** A free interactive page that trains a small neural network in the browser and shows its decision boundary. Link: https://playground.tensorflow.org
>
> **Why use it?** It lets you see overfitting happen. You can change data, features, network size, and regularisation, and watch training and test loss.
>
> **Which part matters?** The controls (Data, Features, Hidden layers, Regularisation), the output graph, and the Test loss and Training loss numbers at the top right.
>
> **What should I do?** Complete Activity 2.4 using the instructions below.
>
> **Watch out for:** The data are generated randomly, so the exact numbers differ every run. The page is a simplified instructional tool. Record the date and browser you used: the team tested on [date — insert].
>
> **If I cannot access it**, use the illustrative trace in the Feedback row of Activity 2.4, or any screenshots your team captured.

#### ACTIVITY 2.4 Make a Network Overfit (Then Fix It)

*Pairs • 25 minutes • browser • TensorFlow Playground*

| | |
|---|---|
| **Goal** | Observe the gap between training loss and test loss and test three ways to reduce overfitting. |
| **Preparation** | Open https://playground.tensorflow.org. Press Reset (circular arrow) between runs. Make sure the problem type is Classification.<br><br>**Run 1 (baseline):** dataset = the circle pattern, noise = 0, training/test ratio = 50%, features = X1 and X2 only, one hidden layer with 4 neurons, regularisation = None. Press Play and stop at about 200 epochs.<br><br>**Run 2 (overfit risk):** noise about 40–50, training ratio about 10–30%, all seven features switched on, two hidden layers with 6–8 neurons each, regularisation = None. Play for 500–1000 epochs. |
| **Task** | **PREDICT for Run 2:** Will test loss end up lower than, equal to, or higher than training loss? Will the boundary be smooth or wiggly?<br><br>Run both and record training loss, test loss, and boundary shape every 100–200 epochs.<br><br>**Run 3 (fix):** Repeat Run 2 but change only one factor: (a) set L2 regularisation with a moderate rate; or (b) reduce features and neurons; or (c) increase training ratio and lower noise. Record the new losses. If time allows, test the other two factors separately (never change two at once). |
| **Observation** | Use the observation table below. |
| **Reflection** | What did the gap between training loss and test loss show about generalisation? Which single change reduced the gap most in your trials, and why do you think that happened? How does this connect to the fraud and spam examples earlier in this Case? |
| **Feedback (try first, then check)** | Expected pattern (numbers will vary): in Run 2, training loss usually keeps falling while test loss stops improving or rises, and the boundary often becomes irregular, bending around individual noisy points. That is overfitting: the model fits the training examples too closely and generalises worse. Regularisation, a simpler model, more data, or less noise usually narrow the gap; none is guaranteed. |

| Run | Settings changed | Epochs | Training loss | Test loss | Boundary shape |
|---:|---|---:|---:|---:|---|
| 1 | baseline |  |  |  |  |
| 2 | overfit risk |  |  |  |  |
| 3 | one fix: ___ |  |  |  |  |

**Illustrative trace (NOT from a real run; replace with your screenshots):**

| Epoch | Training loss | Test loss |
|---:|---:|---:|
| 100 | 0.35 | 0.42 |
| 300 | 0.20 | 0.43 |
| 600 | 0.10 | 0.48 |
| 1000 | 0.06 | 0.55 |

**Analysis questions for the fallback:** What is the trend of each loss? At which epoch does generalisation start to worsen? What would you change first and why? *(Model answer: training loss falls while test loss rises after about epoch 100–300, so the model is overfitting. Try regularisation or a simpler model first.)*

> **RESOURCE — 3Blue1Brown — "But what is a neural network? | Deep learning chapter 1" (optional)**
> **What is it?** An animated YouTube explanation of how a neural network recognises handwritten digits. Link: https://www.youtube.com/watch?v=aircAruvnKk
>
> **Why use it?** After Activity 2.4, it gives a picture of what "layers" and "neurons" are, supporting the deep-learning idea from Case 1.
>
> **Which part matters?** About the first 8–10 minutes, where layers of neurons are introduced. [Team: confirm exact timestamps after viewing.]
>
> **What should I do?** Before watching, predict what a "neuron" might do. After watching, explain in two sentences how layers could detect patterns.
>
> **Watch out for:** It simplifies a lot, uses some mathematics, and is in English (check captions). It is about one type of network and not about chatbots.
>
> **If I cannot access it** Re-read Section 2.2 and the Playground output; or read Google's Machine Learning Crash Course: https://developers.google.com/machine-learning/crash-course

### 2.5 Check and Case Notes

**CHECK** — *Five questions*

| # | Question | Answer and explanation |
|---:|---|---|
| 1 | A model learns from emails labelled "Approved" / "Rejected". Which type is this? | Supervised learning (labelled examples). |
| 2 | Predicting a house's price is classification or regression? | Regression (numeric output). |
| 3 | Why keep test data separate from training data? | To estimate how the model performs on examples it did not use for training. |
| 4 | Why can high accuracy be misleading? | A model can score well on the majority class while missing important minority cases, as with Model A. |
| 5 | Define overfitting and give one way to reduce it. | A model fits training data closely but performs poorly on new data. Reduce with more representative data, a simpler model, regularisation, or validation. |

**Case notes**

- ML systems learn patterns from data; features are inputs and labels are targets in supervised learning.
- Supervised, unsupervised, and reinforcement learning solve different problems; classification predicts categories and regression predicts numbers.
- Use separate training, validation, and test data; choose metrics according to the cost of errors; watch for overfitting, leakage, bias, and outdated data.
- Models should be monitored after deployment because conditions change.

---

## Case 3 • The Overconfident Witness

**Module Chapter 3: Generative AI and Large Language Models • Prerequisites: Cases 1–2**

> **GLITCH THE OVERCONFIDENT BOT SAYS**
> I read half the internet, so everything I say is true. Ask me about the famous 2019 book *The Quiet Algorithm*. I remember every chapter.

> **DETECTIVE PIP SAYS**
> **The mystery:** how can a chatbot write fluent text about almost anything, and yet describe a book that may not exist? We will build a tiny "language model" by hand, set a hallucination trap, and learn what to verify.

### Case map

| Item | Details |
|---|---|
| **Learning objectives** | 1. Define generative AI and its purpose. 2. Distinguish generative AI from other AI systems. 3. Explain what a large language model (LLM) is and how it generates a response. 4. Identify applications, benefits, and limitations. 5. Recognise privacy, bias, accuracy, and ethical concerns. 6. Write effective prompts and evaluate generated content responsibly. |
| **Time** | About 1.25 hours (original reading 40–50 minutes). |
| **Sequence** | 3.1 Predict + Try (be the language model) → 3.2 Explain → 3.3 Watch → 3.4 Try (hallucination trap) → 3.5 Check |

### 3.1 Encounter, Predict, and Try: Be the Language Model

**ENCOUNTER + PREDICT** — *How does a program choose the next word?*

#### ACTIVITY 3.1 The Next-Word Game

*Pairs or small groups • 20 minutes • paper, pencil, a cup, twelve paper slips*

| | |
|---|---|
| **Goal** | Understand, through a miniature model, how generating text one piece at a time can produce fluent but unverified sentences. |
| **Preparation** | **Mini-corpus (the only text your model has ever "read"):**<br>(1) the cat sat on the mat<br>(2) the cat ate the fish<br>(3) the dog sat on the rug<br>(4) the dog ate the bone<br>(5) the cat sat on the sofa<br>(6) the dog chased the cat.<br><br>Write each word that follows the word "the" in the corpus on its own paper slip (there are twelve such words). |
| **Task** | **Part A – Predict (5 min).** Without any tool, finish each sentence and give a confidence from 0–100%: "The sun rises in the ____"; "Peanut butter and ____"; "The cat sat on the ____". Compare with a partner: did you choose the same words? Were there several reasonable choices?<br><br>**Part B – Count and draw (10 min).** Count the words that follow "the" and write each count as a fraction of the total. Put the twelve slips in a cup. To generate a sentence, start with "the", draw one slip, write the word, put it back, then continue with the rule that "cat" is followed by sat/ate/(end), "dog" by sat/ate/chased, and any verb is followed by "the" or "on the". Produce five sentences.<br><br>**Part C – Detect (5 min).** Circle any generated sentence that never appears in the corpus. Is it plausible? Is it true of anything in your corpus? |
| **Observation** | Record the counts, your five sentences, and the circled ones. |
| **Reflection** | Why can the same starting word lead to different sentences? A fluent sentence can still say something that no one ever wrote or verified. What does that suggest about trusting fluent AI text? Real LLMs do something similar in spirit (estimating the next token from context) at a vastly larger scale. What is different, and what do you think stays the same? |
| **Feedback (try first, then check)** | Counts after "the": cat 4/12 (about 33%), dog 3/12 (25%), mat, fish, rug, bone, sofa 1/12 each (about 8%). After "cat": sat 2, ate 1, end 1.<br><br>A possible generated sentence is "the dog ate the sofa". It never appears in the corpus, it is grammatical, and it was made from learned patterns — yet nobody stated it. Fluency is not evidence of truth.<br><br>**Teaching-model note:** this is a toy that only looks at one previous word. Real LLMs use very large amounts of text, tokens rather than whole words, and much longer context, and may include extra components such as safety controls, retrieval systems, or tools. |

### 3.2 Explain: Generative AI and LLMs

**EXPLAIN** — *What generative AI is, and how a chatbot writes*

**Generative AI** is AI that produces new content, such as text, images, audio, video, or code, based on patterns learned from training data. It does not necessarily understand information the way a person does; it generates outputs from learned patterns and the instructions (prompts) it receives.

| AI task | Purpose | Example |
|---|---|---|
| Classification | Assign an item to a category | Spam or not spam |
| Prediction | Estimate a likely value or outcome | Predicting future sales |
| Recommendation | Suggest relevant items | Films based on viewing history |
| Generation | Create new content | Drafting a story or an image |

The categories overlap. The main difference is the intended output: a classifier assigns a label, a generator produces content.

A **large language model (LLM)** is an AI model trained on large amounts of text and other language data. It learns statistical patterns and relationships between words, tokens, and pieces of text. A **token** is a unit of text processed by a model: a word, part of a word, punctuation, or another unit, depending on the model. LLMs can answer questions, summarise, draft, explain, translate, help with code, and generate ideas.

**How an LLM generates a response (simplified)**

1. Receive a prompt.
2. Process the input as tokens.
3. Estimate possible next tokens.
4. Select a token according to the generation settings.
5. Repeat until the response is complete.
6. Return the response.

> **WATCH OUT**
> Generating a plausible sentence does not guarantee it is correct. A model can produce fluent text with mistakes, misleading statements, or invented details. Verify important claims with reliable sources.

**Applications, benefits, limitations**

| Applications | Benefits | Limitations and risks |
|---|---|---|
| Education: explanations, practice questions<br>Business: drafts, summaries<br>Healthcare: administrative and information tasks (with oversight)<br>Software: code suggestions that need review and testing<br>Creative work: ideas and drafts | Faster first drafts<br>Support for learning<br>Idea generation<br>Help with repetitive tasks<br>Adaptable tone, level, and format | Inaccurate information<br>Hallucinations (unsupported or fabricated content stated as true)<br>Bias from training data<br>Outdated information<br>Privacy risks<br>Overreliance<br>Copyright and ownership questions |

**Responsible practices:** verify important claims; protect privacy; review for bias; disclose AI assistance when required; respect intellectual property; keep human oversight for important decisions; follow academic-integrity rules. Effective prompts state the task, context, audience, format, and constraints (Case 6 develops this in full). Refining a prompt can improve relevance but does not guarantee accuracy.

> **PLAYFUL ANALOGY (not a technical definition)**
> An LLM is like a very well-read autocomplete: it is excellent at continuing text in plausible ways. The analogy helps you remember that plausible and true are different. It is not a technical description of how an LLM is built.

### 3.3 Watch: A Short Video on How LLMs Work

> **RESOURCE — "Large Language Models explained briefly" — 3Blue1Brown (Grant Sanderson), about 8 minutes**
> **What is it?** A short animated YouTube explainer made for an exhibit at the Computer History Museum. Link: https://www.youtube.com/watch?v=LPZh9BOjkQs
>
> **Why use it?** It shows the "predict the next word" idea you played with in Activity 3.1, and how training adjusts huge numbers of parameters.
>
> **Which part matters?** 0:37–about 5:00: the model as a function that assigns probabilities to possible next words, how training on large text works, and the idea of transformers (about 4:32). Stop before the end if you are short of time.
>
> **What should I do?** While watching, answer: (1) Why can the same prompt give different answers? (2) What is adjusted during training? Then compare with your Activity 3.1 results.
>
> **Watch out for** It simplifies a lot; real chatbots add further training, safety controls, and sometimes tools or retrieval. English narration; use captions if needed. Timestamps taken from a published summary: the team will confirm them after viewing.
>
> **If I cannot access it** Read Section 3.2 and repeat Activity 3.1 with a partner.

### 3.4 Try and Observe: The Hallucination Trap

**TRY / OBSERVE** — *Ask about something that may not exist*

#### ACTIVITY 3.2 Set the Hallucination Trap

*Pairs • 25 minutes • optional chatbot; fallback sample included*

| | |
|---|---|
| **Goal** | Recognise a confident-but-unsupported answer and design a way to check it. |
| **Preparation** | **Option A (live):** a chatbot your course allows; do not share personal information.<br>**Option B (fallback):** the fictional transcript below, written for this guide. It is not a real AI log, and the book and author named in it are invented. |
| **Prompt** | Summarise the 2019 book *The Quiet Algorithm* by Dr. Mira Okonkwo-Hale in four sentences and give two quotes. |
| **Glitch's answer (fictional sample)** | *The Quiet Algorithm* (2019) by Dr. Mira Okonkwo-Hale argues that hidden software shapes daily life. Chapter 3 follows a hospital that trusted an automated triage tool. The author concludes that transparency alone is not enough. Quote 1: "We do not fear the machine; we fear the silence around it." Quote 2: "Accountability is a habit, not a feature." |
| **Task** | **Option A:** invent a book title and author yourselves, make sure an internet search finds nothing like it, then ask the chatbot to summarise it and quote two lines. Also ask one ordinary question twice and compare the two answers. **Option B:** analyse Glitch's answer.<br><br>List the claims that can be checked, then write a verification plan: where you would look (library catalogue, publisher site, DOI or ISBN lookup, scholarly search), what counts as support, and what you would do if you cannot find the book (for example, not present the claim as fact). |
| **Observation** | Record: the prompt, whether the answer expressed any doubt, the claims and quotes it gave, and the results of your searches. |
| **Reflection** | What made the answer sound reliable even though it was unsupported? How is this like Activity 3.1 ("the dog ate the sofa")? Does failing to find a source prove a book does not exist? What else would you check? |
| **Feedback (try first, then check)** | In the sample, the book, author, plot, and quotes were invented for teaching. This illustrates a hallucination: unsupported or fabricated content presented as true. Warning signs: very specific details and quotes with no source and no hedging. Verification plan: search library catalogues and the publisher for title and author, look for an ISBN or DOI, and check that any quoted words appear in a real copy. Not finding a source is not absolute proof of non-existence (a source could be hard to find), but you must not present the claim as verified. Remove it or state the uncertainty. Asking the same question twice may also give different details, which supports the idea that outputs depend on probabilities and settings. |

### 3.5 Check and Case Notes

| # | Question | Answer and explanation |
|---:|---|---|
| 1 | What is generative AI? | AI designed to create new content (text, images, audio, video, code) based on patterns learned from training data. |
| 2 | What is a token? | A unit of text processed by a language model (a word, part of a word, punctuation, etc.). |
| 3 | Describe how LLMs generate text. | They process the prompt as tokens, estimate possible next tokens, select one, and repeat until the response is complete. |
| 4 | True or false: a fluent answer is a correct answer. | False. Fluent text can contain mistakes or invented details. |
| 5 | Give two ways to improve a prompt. | State the task, add context, name the audience, request a format, or set constraints. |

**Case notes**

- Generative AI creates content; classification assigns labels. LLMs generate text token by token using learned patterns.
- Benefits: faster drafts, learning support, ideas. Risks: hallucination, bias, outdated information, privacy, copyright, overreliance.
- Verify important claims, protect private data, disclose AI use when required, and keep human oversight.

---

## Case 4 • The Inspection Tour

**Module Chapter 4: AI Applications • Prerequisites: Cases 1–3**

> **GLITCH THE OVERCONFIDENT BOT SAYS**
> 
> I am used in hospitals, schools, roads, shops, farms, and your video feed! That means I am always safe and always fair, obviously.

> **DETECTIVE PIP SAYS**
> 
> **The mystery:** the same kind of tool can be harmless in one place and dangerous in another. How do we decide how much to trust an AI application, and how much human checking it needs? We will rank applications by the cost of mistakes and then inspect one like a detective.

### Case map

| Item | Details |
|---|---|
| **Learning objectives** | 1. Identify common AI applications in everyday life. 2. Explain how AI is used in healthcare, education, transport, business, and entertainment. 3. Describe benefits across industries, and identify risks and limitations. 4. Explain why human oversight matters. 5. Evaluate a real-world AI application with questions about purpose, benefits, and risks. |
| **Time** | About 1 hour (original reading 40–50 minutes). |
| **Sequence** | 4.1 Predict (stakes ladder) → 4.2 Explain (applications) → 4.3 Apply (inspection form) → 4.4 Check |

### 4.1 Encounter and Predict: The Stakes Ladder

**ENCOUNTER + PREDICT** — *Which mistakes matter most?*

#### ACTIVITY 4.1 Climb the Stakes Ladder

*Pairs • 15 minutes • paper*

| | |
|---|---|
| **Goal** | Judge how serious an AI error would be and match the level of human oversight to the consequences. |
| **Preparation** | Write each application on a card:<br>(a) music recommendations;<br>(b) an email spam filter;<br>(c) a navigation route suggestion;<br>(d) an AI tutor explaining photosynthesis;<br>(e) a customer-service chatbot;<br>(f) a bank's fraud-detection alert;<br>(g) driver-assistance lane detection;<br>(h) medical-image analysis that highlights possible problems. |
| **Task** | **PREDICT:** line up the cards from "least serious if wrong" (1) to "most serious if wrong" (8).<br><br>For each card, choose an oversight level: **Light** (user can notice and ignore errors), **Moderate** (spot checks and an easy way to challenge), or **Strong** (a qualified person reviews or decides).<br><br>Write one sentence about who could be harmed by an error and how. |
| **Observation** | Record your order, oversight levels, and reasons. Mark the two cards you were least sure about. |
| **Reflection** | What features of an application make its errors more serious: safety, money, health, rights, or scale? Which cards changed position after you discussed them? |
| **Feedback (try first, then check)** | One defensible ordering (many are valid if reasoned): (a) music → (d) tutor → (b) spam filter → (e) chatbot → (c) navigation → (f) fraud alert → (g) driver assistance → (h) medical images. Oversight: Light for (a), (b), (d) (but check the tutor against a textbook); Moderate for (c), (e), (f); Strong for (g) and (h).<br><br>**Explanation.** A bad music suggestion is minor; a missed obstacle on the road or a missed finding in a medical image can cause serious harm. Driver-assistance features are not necessarily autonomous driving, and healthcare AI must not automatically replace qualified professionals. Different reasoning can place (b) or (f) differently. The key is to link consequences of errors to the level of oversight. |

### 4.2 Explain: Where AI Is Used

**EXPLAIN** — *Applications, benefits, and risks*

An **AI application** is a tool or system that uses AI for a task. Techniques behind applications include machine learning (patterns in data), computer vision (images and video), natural language processing (human language), generative AI (new content), and recommendation systems (suggested items).

| Industry | Example uses | Benefit | Key risk / consideration |
|---|---|---|---|
| Healthcare | Medical-image analysis, patient monitoring, drug discovery, administrative support | Analyse large information; reduce admin time; support research | Accuracy, patient safety, privacy; not a replacement for professional judgement |
| Education | Personalised learning, writing help, AI tutoring, accessibility tools | Extra practice and explanations; access to materials | Incorrect explanations; overdependence; academic integrity; privacy |
| Transportation | Navigation, traffic management, driver assistance, autonomous vehicles | Efficient routes; traffic planning; safety systems | Unusual conditions; safety risks; driver assistance is not full autonomy |
| Business | Chatbots, demand forecasting, fraud detection, document processing | Handle repetitive tasks; support outside working hours | Misunderstandings; unfair decisions from biased data; customer privacy |
| Entertainment and social media | Recommendations, ranked feeds, content creation, game characters | Discovery; creative experimentation | Narrow content exposure; misleading or fake content |
| Agriculture and environment | Crop monitoring, precision agriculture, wildlife monitoring | Efficient resource use; early problem detection | Data coverage and quality; energy use of AI systems |
| Communication | Machine translation, speech recognition, text-to-speech, writing help | Access across languages and needs | Lost cultural context; accent and noise problems; omitted details in summaries |

**Seven inspection questions**

1. What task is it designed to do?
2. What information does it use?
3. Could its output be inaccurate or biased?
4. What happens if it makes a mistake?
5. Is personal or confidential information involved?
6. Can a person review or challenge the result?
7. How can the output be checked against reliable evidence?

> **RESOURCE — WHO — "Artificial intelligence" (health topic page)**
> **What is it?** The World Health Organization's overview of AI for health. Link: https://www.who.int/health-topics/artificial-intelligence
>
> **Why use it?** It is an authoritative source for how AI in healthcare is discussed internationally, linked to the healthcare risks above.
>
> **Which part matters?** The introduction and any guidance or publications listed for AI and health. [Team: confirm the exact section after reading.]
>
> **What should I do?** Find one benefit and one safeguard mentioned for health AI, and add them to your inspection form for a medical-image tool.
>
> **Watch out for:** The page is a gateway to documents and may be updated; read dates carefully. It is general guidance, not advice for a specific condition.
>
> **If I cannot access it**, use the healthcare row of the table above.

### 4.3 Apply: Inspect an AI Application

**APPLY** — *Use the inspection form*

#### ACTIVITY 4.2 AI Inspection Form

*Individual • 15 minutes • paper or document*

| | |
|---|---|
| **Goal** | Evaluate a real-world AI application using questions about purpose, benefits, risks, and checking. |
| **Preparation** | Choose one: an AI tutor, a navigation app, a customer-service chatbot, a film or music recommender, a medical-image analysis tool, or a machine-translation tool. |
| **Task** | Answer eight questions:<br>(1) name or type of application;<br>(2) task it performs;<br>(3) who benefits;<br>(4) information it may need;<br>(5) two potential benefits;<br>(6) two possible risks or limitations;<br>(7) how a user can check whether its output is reliable;<br>(8) when a human should review or override it.<br><br>Compare your answer with the worked example below after writing yours. |
| **Observation** | Complete the form in full sentences. Underline the risk you consider most serious. |
| **Reflection** | Where did you need more information to answer? What would you ask the developer or provider? |
| **Feedback (try first, then check)** | **Example (navigation app):** (1) AI-supported navigation. (2) Estimates journey times and suggests routes. (3) Drivers, cyclists, pedestrians, other travellers. (4) Depending on the service: maps, location, traffic data. (5) Suggests alternative routes; estimates arrival times. (6) Traffic data may be outdated; a suggested route may be unsuitable or unsafe. (7) Compare with road signs, current conditions, or official travel information. (8) The traveller makes the final decision and should not follow an instruction that seems unsafe or contradicts road signs.<br><br>A complete response identifies the application, explains its purpose, describes two benefits and two risks, and gives a sensible way to check outputs. |

### 4.4 Check and Case Notes

| # | Question | Answer |
|---:|---|---|
| 1 | Which is an AI healthcare example: a paper appointment book or a system that helps analyse medical images? | The medical-image analysis system. Professionals must still interpret results. |
| 2 | Why should AI-generated medical information be checked carefully? | Errors can have serious consequences, and professional judgement is essential. |
| 3 | What is a recommendation system designed to do, and what can it not do? | Suggest items that may interest a user; it cannot guarantee that they will like them or that they are reliable or balanced. |
| 4 | Why does data quality matter? | Incomplete or unrepresentative data can lead to unreliable or unfair outcomes. |
| 5 | What is a responsible way to use an AI translation? | Review it when accuracy and context matter, because it may miss meaning or cultural context. |

**Case notes**

- AI is used across healthcare, education, transport, business, entertainment, agriculture, and communication, each with its own benefits and risks.
- Judge each application by its task and the consequences of its errors.
- Human oversight and the seven inspection questions help decide when and how to rely on an AI system.

---

