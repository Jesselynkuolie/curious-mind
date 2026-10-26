
# Chapter 3: Generative AI and Large Language Models (LLMs)

## Chapter Overview

Generative artificial intelligence (generative AI) is a type of AI that creates new content, such as text, images, audio, video, and computer code. Large language models (LLMs) are a category of AI models designed to process and generate language.

These technologies are used in writing assistants, chatbots, summarization tools, coding assistants, and many other applications. Understanding how they work, what they can do, and where they can fail helps learners use them effectively and responsibly.

This chapter introduces generative AI, explains the basic principles behind LLMs, explores practical applications, and develops skills for evaluating AI-generated content.

## Learning Objectives

By the end of this chapter, learners should be able to:

1. Define generative AI and explain how it differs from other AI systems.
2. Describe the basic operating principles of a large language model.
3. Explain the roles of training data, tokens, and prompts.
4. Identify common applications and limitations of generative AI.
5. Evaluate AI-generated content for accuracy, bias, and reliability.
6. Apply responsible practices when using generative AI tools.

## 1. What Is Generative AI?

Generative AI refers to AI systems that produce new content based on patterns learned from training data and, in some cases, additional information supplied at the time of use.

Examples of generated content include:

- **Text:** explanations, summaries, outlines, and draft emails.
- **Images:** illustrations, concept art, and design mock-ups.
- **Audio:** synthesized speech, music, and sound effects.
- **Video:** generated or edited video clips.
- **Code:** code suggestions, examples, and explanations.

Generative AI does not simply retrieve a fixed answer from a database in every case. It generates outputs using patterns learned during training and the context provided to the system. Some systems also use external tools or retrieve information from documents and websites.

### Generative AI Compared with Other AI Systems

Traditional AI applications can be designed to classify, predict, detect, or recommend. Generative AI focuses on producing content, although modern systems can combine several capabilities.

| AI task | Example | Main purpose |
|---|---|---|
| Classification | Identifying whether an email is spam | Assign an item to a category |
| Prediction | Estimating future product demand | Estimate a likely outcome |
| Recommendation | Suggesting a film | Recommend relevant options |
| Generation | Drafting an explanation | Create new content |

These categories can overlap. For example, a single AI application might classify a request, retrieve relevant information, and generate a response.

### Example

A spam filter estimates whether an incoming email is unwanted. A generative AI assistant can draft a reply to an email. The first task is classification; the second is content generation.

**Key idea:** Generative AI is defined by its ability to generate content, not by a guarantee that the content is accurate or original in every meaningful sense.

## 2. What Is a Large Language Model?

A large language model (LLM) is a model trained on large amounts of text or other language-related data to learn statistical and structural patterns in language.

Many modern LLMs use a neural-network architecture called a **Transformer**. Transformer-based models use mechanisms such as attention to help represent relationships between tokens in a sequence.

An LLM can perform tasks such as:

- Answering questions.
- Summarizing documents.
- Rewriting text in a different style.
- Translating between languages.
- Generating ideas and outlines.
- Explaining or suggesting computer code.

An LLM is not the same thing as an entire AI application. An application may combine an LLM with a user interface, system instructions, external tools, safety measures, and document retrieval.

### How Does an LLM Generate Text?

Many LLMs generate text by repeatedly estimating the probability of a next token based on the preceding context. A token may be a whole word, part of a word, punctuation, or another text unit.

A simplified process is:

1. The user submits a prompt.
2. The system converts the text into tokens.
3. The model processes the available context.
4. The model estimates possible next tokens.
5. A decoding method selects a token.
6. The process repeats until the response ends or a stopping condition is reached.

The exact process varies across models and applications. Some systems also use tools, retrieved documents, or multimodal inputs such as images and audio.

### A Simple Illustration

Suppose a prompt begins:

> The sun rises in the ...

A language model may assign a high probability to the token “east” because that continuation fits common language patterns and general knowledge.

This example illustrates next-token prediction. Real responses are much more complex and depend on the model, prompt, context, and decoding settings.

**Important:** Predicting likely text does not guarantee that every statement is true. Fluent language and factual accuracy are different qualities.

## 3. Important Concepts Behind LLMs

### 3.1 Training Data

Training data provides examples from which a model learns patterns. Depending on the model, training data may include text, code, images, audio, or other data types.

The quality, coverage, and limitations of training data can influence model performance. Data may contain errors, gaps, stereotypes, outdated information, or underrepresented perspectives.

Training data also raises questions about privacy, consent, copyright, and the suitability of the material used.

### 3.2 Tokens

Tokens are the units of text that a model processes. A token is not necessarily a complete word.

For example, a long or uncommon word may be split into multiple tokens, while a short common word may be represented by one token.

Tokenization affects how text is processed and how much text fits within a model's context window. The exact tokenization method differs between models.

### 3.3 Prompts and Context

A prompt is the instruction or input given to an AI system. Context may also include earlier messages, supplied documents, system instructions, or information retrieved by an application.

Clear prompts can improve the relevance and usefulness of outputs.

A useful prompt often specifies:

- **Task:** What should the AI do?
- **Context:** What background information does it need?
- **Audience:** Who will use the result?
- **Constraints:** What length, format, or limitations should apply?
- **Output format:** Should the response be a list, table, explanation, or another format?

#### Example of Prompt Improvement

**Weak prompt:**

> Explain AI.

**Improved prompt:**

> Explain the difference between artificial intelligence, machine learning, and generative AI for a beginner. Use simple language, give one everyday example of each, and finish with three short review questions.

The improved prompt defines the task, audience, scope, and desired format. It can produce a more useful answer, although it still requires review.

### 3.4 Model Training and Fine-Tuning

Training is the process through which a model's parameters are adjusted using data and a learning objective.

Some models also undergo additional stages, such as fine-tuning, to improve performance on particular tasks or to adapt the model's behavior. Instruction tuning and preference-based optimization are examples of techniques used in some systems.

These stages differ across model developers. Not every model is trained or adapted in the same way.

### 3.5 Context Window

A context window is the amount of information a model can process as context for a particular interaction. It may include the current prompt, conversation history, and other supplied information.

If relevant information falls outside the available context, the system may not take it into account. Applications can manage this limitation by selecting, summarizing, or retrieving relevant information.

## 4. Common Applications of Generative AI

### Education

Generative AI can help explain difficult concepts, create practice questions, suggest study plans, and provide feedback on drafts.

**Limitation:** Explanations and answers may contain mistakes. Learners should check important claims and follow their institution's rules about AI assistance.

### Business and Communication

Organizations may use generative AI to draft communications, summarize documents, brainstorm ideas, or support customer-service workflows.

**Limitation:** Confidential information should not be entered into a tool unless its data-handling rules and the organization's policies permit it.

### Software Development

AI coding assistants can suggest code, explain programming concepts, generate tests, and help investigate errors.

**Limitation:** Suggested code may contain bugs, security weaknesses, licensing concerns, or incorrect assumptions. It should be tested and reviewed before use.

### Creative Work

Generative tools can support brainstorming, illustration, design exploration, and the production of audio or video drafts.

**Limitation:** Users should consider copyright, permission, attribution, consent, and the possibility of misleading or deceptive media.

### Research and Information Work

AI tools can help organize notes, summarize supplied documents, and identify questions for further investigation.

**Limitation:** A generated summary may omit important context or misrepresent a source. Verify important statements against the original material.

## 5. Limitations and Risks

Generative AI is useful, but it has limitations that users must understand.

### 5.1 Hallucinations and Fabricated Information

A hallucination is an output that presents incorrect, fabricated, or unsupported information as if it were true. Examples include invented references, inaccurate explanations, and false claims about events.

**How to reduce the risk:**

1. Check important claims against reliable sources.
2. Open and verify cited references.
3. Ask the system to distinguish known information from uncertainty.
4. Avoid relying on generated content alone for high-impact decisions.

A confident tone is not evidence of correctness.

### 5.2 Bias and Representation

Models can reproduce or amplify patterns and biases present in their training data or introduced by system design and use.

Bias may affect the language, examples, recommendations, or assumptions in an output.

**How to reduce the risk:**

- Review outputs for stereotypes and unfair assumptions.
- Consider perspectives that may be missing.
- Compare outputs with reliable evidence.
- Use appropriate human review in consequential settings.

### 5.3 Privacy and Confidentiality

Prompts may contain personal information, business information, student records, or other sensitive data.

Before using a tool, review its privacy settings, data-handling practices, and applicable organizational policies.

Do not enter confidential or personal information unless you have the necessary authorization and the tool is approved for that use.

### 5.4 Copyright and Ownership

Generated outputs may raise questions about copyright, ownership, attribution, and similarity to existing works. Legal requirements vary by jurisdiction and situation.

Users should check the relevant tool terms, licences, applicable law, and institutional rules before publishing or distributing generated material.

### 5.5 Overreliance

Depending too heavily on AI can weaken independent reasoning or cause users to accept incorrect suggestions.

Use AI as a tool to support learning and work, rather than as a substitute for understanding, verification, or professional judgment.

## 6. Practical Activity: Improve and Evaluate a Prompt

### Objective

Practice writing a clear prompt and evaluating the quality of a generated response.

### Instructions

1. Choose a topic you understand, such as renewable energy, healthy study habits, or basic computer security.
2. Write an initial prompt asking an AI tool to explain the topic.
3. Improve the prompt by specifying the intended audience, required examples, and output format.
4. Compare the two responses.
5. Identify at least two claims that should be checked.
6. Verify those claims using reliable sources.
7. Record one limitation or possible bias in the response.

### Activity Worksheet

**Topic:** [Enter your chosen topic]

**Initial prompt:**

[Write your first prompt.]

**Improved prompt:**

[Write your revised prompt.]

**What improved?**

[Explain how the changes affected clarity, relevance, or usefulness.]

**Claims checked:**

1. [Claim and verification source]
2. [Claim and verification source]

**Limitation identified:**

[Explain one weakness, uncertainty, omission, or possible bias.]

**Reflection:**

What did you learn about the difference between a useful AI-generated answer and a verified answer?

### Expected Learning Outcome

Learners should be able to improve a prompt, compare outputs critically, and explain why important information requires verification.

## 7. Knowledge Check

Answer the questions before reviewing the answer key.

### Question 1

What is the main purpose of generative AI?

A. To store every possible answer in a database  
B. To generate content based on learned patterns and available context  
C. To guarantee that all information is accurate  
D. To eliminate the need for human judgment

### Question 2

What is a large language model?

A. A type of model designed to process and generate language  
B. A database containing only verified facts  
C. A computer operating system  
D. A tool that can only classify images

### Question 3

What is a token in language-model processing?

A. A guarantee that an answer is correct  
B. A unit of text processed by a model  
C. A citation to an academic paper  
D. A type of computer virus

### Question 4

Why should AI-generated references be checked?

A. All AI references are automatically correct  
B. References are never useful  
C. A model may generate inaccurate or nonexistent citations  
D. Checking references makes the model stop working

### Question 5

Which prompt is generally more useful?

A. "Do something."  
B. "Explain machine learning to a beginner in 150 words and give two examples."  
C. "Write anything you want."  
D. "Give me an answer without context."

### Question 6

Which action is most responsible when using AI-generated information for an important report?

A. Submit the output without reading it  
B. Trust it if the language sounds confident  
C. Verify key claims, check sources, and review the result  
D. Remove all references

### Question 7

Name two potential risks of generative AI and describe one way to reduce each risk.

### Question 8

Explain why a well-written AI response may still be inaccurate.

## 8. Answer Key and Explanations

### Question 1: B

Generative AI produces content using patterns learned during training and the context available at generation time. It does not guarantee that the output is correct.

### Question 2: A

An LLM is a model designed to process and generate language. It may be part of a larger application that includes other tools and capabilities.

### Question 3: B

A token is a unit of text processing. Depending on the tokenizer, it may represent a whole word, part of a word, punctuation, or another text unit.

### Question 4: C

Generated references can be incomplete, inaccurate, or fabricated. Check that each source exists and supports the claim attributed to it.

### Question 5: B

The prompt identifies the topic, audience, approximate length, and desired examples. These details help define the expected output.

### Question 6: C

Important claims should be verified, sources reviewed, and the final result checked by a responsible person.

### Question 7: Sample answer

- **Hallucination:** Verify important claims against reliable sources.
- **Bias:** Examine the output for unfair assumptions and consider alternative perspectives.

Other well-explained risks and reasonable mitigation strategies are acceptable.

### Question 8: Sample answer

A model can generate fluent text by learning language patterns without guaranteeing that every statement is factually correct. A response may sound convincing while containing unsupported claims, outdated information, or fabricated references.

## 9. Chapter Summary

In this chapter, learners explored the principles and practical use of generative AI and large language models.

Key takeaways:

- Generative AI creates content such as text, images, audio, and code.
- LLMs process and generate language using patterns learned during training.
- Tokens, prompts, context, and training data influence model behavior.
- Clear prompts can improve the relevance and usefulness of outputs.
- Generative AI can support education, communication, research, creative work, and software development.
- Outputs can contain hallucinations, bias, privacy risks, and copyright-related concerns.
- Important information should be verified, and human judgment remains essential.

The central lesson is to use generative AI thoughtfully: define the task clearly, evaluate the output critically, and verify important claims before relying on them.

## 10. Key Terms

| Term | Definition |
|---|---|
| Generative AI | AI that generates content based on learned patterns and available context |
| Large language model (LLM) | A model designed to process and generate language |
| Token | A unit of text processed by a model |
| Prompt | An instruction or input supplied to an AI system |
| Context window | The amount of information a model can process as context for an interaction |
| Training data | Data used to train a model |
| Fine-tuning | Additional training used to adapt a model to particular tasks or behaviors |
| Hallucination | Generated content that is incorrect, fabricated, or unsupported but presented as plausible |
| Bias | A systematic skew that can lead to unfair or unrepresentative outputs |
| Verification | Checking information against reliable evidence or sources |

## 11. References and Further Reading

The following sources provide background on generative AI, language models, and responsible AI use.

1. Vaswani, A., et al. (2017). *Attention Is All You Need.* Advances in Neural Information Processing Systems.  
   https://doi.org/10.48550/arXiv.1706.03762

2. National Institute of Standards and Technology (NIST). (2023). *Artificial Intelligence Risk Management Framework (AI RMF 1.0).*  
   https://doi.org/10.6028/NIST.AI.100-1

3. UNESCO. (2023). *Guidance for Generative AI in Education and Research.*  
   https://unesdoc.unesco.org/ark:/48223/pf0000386693

4. OECD. *OECD AI Principles.*  
   https://oecd.ai/en/ai-principles

Check each reference and ensure that it is used appropriately in the final learning materials. Add any further sources needed to support specific factual claims.

## 12. Chapter Quality Checklist

- [ ] Learning objectives are clear and assessable.
- [ ] Explanations are appropriate for the target audience.
- [ ] Examples support the learning objectives.
- [ ] The practical activity includes clear instructions.
- [ ] Knowledge-check questions align with the objectives.
- [ ] Answers include explanations.
- [ ] The chapter summary reflects the main ideas.
- [ ] Factual claims and references have been checked.
- [ ] Accessibility and Markdown formatting have been reviewed.
- [ ] The chapter aligns with `content/00-module-outline.md`.

## 13. Completion Status

This chapter provides a structured learning resource on generative AI and LLMs. Before submission, review it against the course outline, verify its references, and complete the quality checklist based on actual checks.

The chapter should be considered complete only after the content, sources, activities, and formatting have been reviewed.
