```markdown
# Chapter 3: Generative AI and Large Language Models (LLMs)

## 3.1 Introduction

Generative artificial intelligence (generative AI) is a type of AI that can create new content, such as text, images, audio, video, and computer code. These systems learn patterns from training data and use those patterns to generate new outputs in response to instructions or prompts.

Large language models (LLMs) are a type of AI model designed to process and generate human language. They can help users summarise information, answer questions, draft text, translate languages, and generate computer code.

Generative AI tools are increasingly used in education, business, healthcare research, software development, and creative work. However, their outputs are not always accurate, unbiased, or appropriate. Understanding how these systems work and how to evaluate their responses is essential for responsible use.

This chapter introduces generative AI, explains the basic principles behind LLMs, explores their applications and limitations, and provides practical guidance for writing effective prompts.

**Estimated learning time:** 40–50 minutes

## 3.2 Learning Objectives

By the end of this chapter, learners should be able to:

1. Define generative AI and explain its main purpose.
2. Distinguish generative AI from other types of AI systems.
3. Explain what a large language model is at a high level.
4. Describe how an LLM generates a response.
5. Identify common applications of generative AI.
6. Explain the benefits and limitations of generative AI.
7. Recognise privacy, bias, accuracy, and ethical concerns.
8. Write effective prompts and evaluate AI-generated content responsibly.

## 3.3 What Is Generative AI?

Generative AI refers to AI systems that produce new content based on patterns learned from training data.

Depending on the system, the generated content may include:

- Text, such as explanations, summaries, and stories.
- Images, such as illustrations and concept art.
- Audio, such as speech or music.
- Video, such as short generated clips.
- Computer code, such as example functions or scripts.

Generative AI does not necessarily understand information in the same way that a human does. It generates outputs based on learned patterns and the instructions it receives.

### Example

A user enters the prompt:

"Explain artificial intelligence in simple language for a beginner."

A generative AI tool may produce a short explanation using accessible vocabulary and examples.

The user can then request a shorter explanation, ask for an analogy, or request a quiz to check their understanding.

### Key Point

Generative AI creates content, but the generated content should be checked before it is trusted or used.

## 3.4 Generative AI and Traditional AI

AI systems can be designed for different purposes. Some systems primarily classify information or make predictions, while generative systems create new content.

| AI task | Purpose | Example |
|---|---|---|
| Classification | Assign an item to a category | Classifying an email as spam or not spam |
| Prediction | Estimate a likely value or outcome | Predicting future sales from historical data |
| Recommendation | Suggest relevant items | Recommending films based on viewing history |
| Generation | Create new content | Drafting a story or generating an image |

These categories can overlap. For example, a generative AI system may also use classification or prediction components.

The main difference is the intended output: a classification system assigns a label, while a generative system produces content.

## 3.5 What Are Large Language Models?

A large language model (LLM) is an AI model trained on large amounts of text and other language data. It learns statistical patterns and relationships between words, tokens, and pieces of text.

LLMs can perform tasks such as:

- Answering questions.
- Summarising documents.
- Drafting emails and reports.
- Explaining unfamiliar concepts.
- Translating text.
- Helping with computer programming.
- Generating ideas and outlines.

Some LLMs can also process images or other types of input. Their capabilities depend on the model and the tools connected to it.

### What Is a Token?

A token is a unit of text processed by a language model. A token may represent a word, part of a word, punctuation, or another text unit.

For example, a sentence is divided into tokens before it is processed. The exact tokenisation depends on the model.

Understanding tokens helps explain why language models process text in units rather than treating every sentence as a single indivisible object.

## 3.6 How Do LLMs Generate Text?

Many LLMs generate text by repeatedly estimating which token should come next, given the preceding context.

A simplified process is:

1. **Receive a prompt:** The user provides a question or instruction.
2. **Process the input:** The model converts the input into tokens and processes their relationships.
3. **Estimate possible next tokens:** The model calculates probabilities for possible continuations.
4. **Select a token:** A token is selected according to the model's generation settings
