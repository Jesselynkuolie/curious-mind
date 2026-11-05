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
- [Case 1 • Is It Really AI?](#case-1--is-it-really-ai)
  - [1.1 Encounter and Predict: Glitch's Card Pile](#11-encounter-and-predict-glitchs-card-pile)
  - [1.2 Explain: What Is AI?](#12-explain-what-is-ai)
- [Case 2 • The Fraud Alarm](#case-2--the-fraud-alarm)
- [Case 3 • The Overconfident Witness](#case-3--the-overconfident-witness)
- [Case 4 • The Inspection Tour](#case-4--the-inspection-tour)
- [Case 5 • The School Predictor Dispute](#case-5--the-school-predictor-dispute)
- [Case 6 • The Prompt Workshop](#case-6--the-prompt-workshop)
- [Glossary](#glossary)
- [Resource Directory and Access Notes](#resource-directory-and-access-notes)
- [References and Acknowledgements](#references-and-acknowledgements)

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

## 1.2 AI, Machine Learning, and Deep Learning

These terms are related, but they do not mean the same thing.

- **Artificial Intelligence (AI):** The broad field of creating computer systems that perform tasks associated with intelligent behavior.
- **Machine Learning (ML):** An approach within AI that allows systems to learn patterns from data.
- **Deep Learning (DL):** A type of machine learning that uses neural networks with multiple processing layers to learn complex patterns.

**Remember the relationship:** Deep learning is a type of machine learning, and machine learning is a part of the broader field of AI.

## 1.3 AI Compared with Rule-Based Automation

Traditional rule-based programs follow instructions explicitly specified by their developers. Machine learning systems, by contrast, use patterns learned from training data to make predictions or decisions.

For example:

- A basic calculator follows programmed mathematical rules.
- A machine learning spam filter uses patterns learned from examples to estimate whether a new email is spam.

Not every automated task uses AI, and not every AI system uses machine learning.

## Key Points to Remember

- AI is a broad field, not a single application.
- Machine learning is one approach used to develop AI systems.
- Deep learning is a type of machine learning.
- AI systems can make errors and should not automatically be treated as reliable sources of truth.

## Review Questions

1. What is Artificial Intelligence?
2. Explain the relationship between AI, machine learning, and deep learning.
3. Give one example of a rule-based program and one example of a machine learning system.
4. Why should users check information produced by AI?

## Learning Activity

Identify three digital tools you use in everyday life. For each tool:

1. Describe what the tool does.
2. Decide whether the feature you identified uses AI, ordinary automation, or whether you need more information to tell.
3. Explain your reasoning.

Do not assume that a tool uses AI simply because it is digital or automated.

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
