# Chapter 2: Machine Learning Basics

**Module:** Introduction to Artificial Intelligence  
**Level:** Beginner  
**Estimated learning time:** 40–50 minutes  
**Prerequisites:** Chapter 1 — What Is AI?

---

## 2.1 Introduction

Machine learning (ML) is one of the most important areas of artificial intelligence. It allows computer systems to identify patterns in data and use those patterns to make predictions, classify information, or support decisions.

Machine learning is used in many everyday applications. Email services use it to identify possible spam, streaming platforms use it to recommend content, and navigation systems use data to estimate travel times.

Understanding machine learning helps us recognise what these systems can do, how they learn from data, and why their predictions are not always correct.

In this chapter, you will explore the basic principles of machine learning, the different types of learning, how models are trained and evaluated, and the importance of data quality.

### Learning objectives

By the end of this chapter, you should be able to:

1. Define machine learning and explain its relationship to AI.
2. Describe the roles of data, features, labels, and models.
3. Distinguish supervised learning, unsupervised learning, and reinforcement learning.
4. Explain the difference between classification and regression.
5. Describe the basic stages of training and evaluating a model.
6. Explain overfitting and why a model must be tested on unseen data.
7. Identify how data quality and bias can affect machine learning results.

---

## 2.2 What Is Machine Learning?

Machine learning is a field of AI in which computer systems use data to learn patterns and perform tasks without requiring every decision to be explicitly programmed as a separate rule.

In traditional rule-based programming, a developer specifies instructions for the computer to follow. In machine learning, a learning algorithm uses examples or experience from data to build a model that can make predictions or identify patterns.

### Example: Identifying spam emails

Imagine that you want to create a system that identifies spam emails.

A rule-based system might flag an email if it contains certain words or comes from a known suspicious address. Such rules can be useful, but spammers may change their wording or methods.

A machine learning system can instead be trained using examples of emails labelled as spam or not spam. It can learn patterns associated with each category and use those patterns to classify new emails.

The model may consider factors such as the words used, links included, sender information, and other relevant features.

However, the system will not necessarily classify every email correctly. Some legitimate messages may be flagged as spam, and some spam messages may reach the inbox.

### Key point

Machine learning can identify useful patterns in data, but its results depend on the data, learning method, and evaluation process.

---

## 2.3 How AI, Machine Learning, and Deep Learning Relate

Artificial intelligence, machine learning, and deep learning are related concepts, but they do not mean exactly the same thing.

- **Artificial intelligence (AI):** The broad field of developing systems that perform tasks associated with capabilities such as reasoning, perception, prediction, and language processing.
- **Machine learning (ML):** An area of AI in which systems learn patterns from data.
- **Deep learning:** A type of machine learning that uses neural networks with multiple layers to learn complex patterns.

Deep learning is particularly useful for tasks involving images, speech, language, and other complex data.

### Example

A photo application may use AI to identify people, objects, or scenes.

The image-recognition feature could use a machine learning model. If that model uses a neural network with many layers, it may be described as a deep learning model.

### Remember

Deep learning is part of machine learning, and machine learning is part of the broader field of AI. Not every AI system uses machine learning, and not every machine learning system uses deep learning.

---

## 2.4 Important Machine Learning Terms

Before exploring how machine learning works, it is helpful to understand several key terms.

| Term | Definition | Example |
|---|---|---|
| Data | Information used to develop or operate a system. | A collection of emails. |
| Dataset | An organised collection of data. | Thousands of labelled email examples. |
| Feature | An input characteristic used by a model. | The number of links in an email. |
| Label | The known target or category associated with an example in supervised learning. | “Spam” or “Not spam.” |
| Algorithm | A procedure or set of methods used to learn patterns or solve a problem. | An algorithm that learns to classify emails. |
| Model | A learned representation of patterns that can be used to make predictions or decisions. | A trained email classifier. |
| Training | The process of using data to adjust a model's parameters. | Learning from labelled emails. |
| Prediction | An output produced by a model for new input. | Classifying a new email as likely spam. |
| Evaluation | Measuring how well a model performs on relevant data. | Checking how often the model classifies emails correctly. |

Features and labels are especially important in supervised learning. Features provide the input information, while labels provide the target answers from which the model learns.

---

## 2.5 How Does Machine Learning Work?

Although different machine learning methods operate in different ways, a typical project follows several stages.

### Stage 1: Define the problem

First, decide what the system should accomplish.

For example, an organisation may want to predict whether a customer is likely to cancel a subscription.

A clear problem definition helps determine what data is needed and how success should be measured.

### Stage 2: Collect data

Next, gather relevant data.

For a subscription-cancellation model, the data might include subscription length, usage patterns, and previous cancellation records.

The data should be collected lawfully and handled in accordance with relevant privacy requirements.

### Stage 3: Prepare the data

Raw data may contain missing values, duplicate records, errors, or irrelevant information.

Data preparation involves checking and organising the information before it is used to train the model.

For example, duplicate customer records might need to be removed, and missing values may need to be investigated.

### Stage 4: Select a learning method

Choose a method that fits the task and available data.

If the goal is to predict whether a customer will cancel a subscription, a classification model may be suitable.

If the goal is to estimate the amount a customer will spend, a regression model may be more appropriate.

### Stage 5: Train the model

The learning algorithm uses training data to identify patterns and adjust the model's parameters.

The resulting model represents patterns learned from the examples.

### Stage 6: Evaluate the model

The model is tested using data that was not used to train it.

Evaluation helps determine whether the model can make useful predictions on new examples.

### Stage 7: Use and monitor the model

After evaluation, a model may be deployed in a real application.

Its performance should be monitored because data and real-world conditions can change over time. A model that once performed well may become less reliable if the patterns it learned no longer reflect the current situation.

### Summary of the process

**Define the problem → Collect data → Prepare data → Select a method → Train → Evaluate → Deploy and monitor**

These stages may be repeated. If the model performs poorly, the team may need better data, a different learning method, or a clearer problem definition.

---

## 2.6 Types of Machine Learning

Machine learning is commonly divided into supervised learning, unsupervised learning, and reinforcement learning.

Each type addresses different kinds of problems.

### 2.6.1 Supervised Learning

Supervised learning uses examples that include both input data and known target answers, called labels.

The model learns relationships between the inputs and labels. It can then use those learned relationships to predict labels or values for new inputs.

**Example: Email classification**

A dataset contains emails labelled as “Spam” or “Not spam.” A model learns patterns from these examples and uses them to classify new emails.

Other examples include:

- Predicting house prices from property information.
- Classifying images into categories.
- Predicting whether a transaction may be fraudulent.

Supervised learning is useful when suitable labelled examples are available.

### 2.6.2 Unsupervised Learning

Unsupervised learning works with data that does not have predefined target labels for the task.

The system attempts to identify patterns, structures, or groupings in the data.

**Example: Grouping customers**

A retailer has information about customer purchases but does not have predefined customer-group labels. An unsupervised learning method may group customers with similar purchasing patterns.

The resulting groups can help the retailer explore customer behaviour.

Other examples include:

- Grouping similar documents.
- Exploring patterns in scientific data.
- Identifying unusual observations that require further investigation.

The groups or patterns discovered by an unsupervised method are not automatically meaningful. People may need to examine and interpret the results.

### 2.6.3 Reinforcement Learning

Reinforcement learning involves an agent learning how to act through interaction with an environment.

The agent takes actions and receives feedback in the form of rewards or penalties. Over time, it learns a strategy intended to maximise the cumulative reward.

**Example: Learning to play a game**

A game-playing agent tries different actions. Actions that contribute to winning may receive positive rewards, while unsuccessful actions may receive little or negative reward. The agent learns a strategy through repeated interaction.

Other applications may include robotics, resource management, and simulated control tasks.

Reinforcement learning differs from supervised learning because it does not simply learn from a dataset of correct answers for every input. Instead, it learns from the consequences of actions.

### Comparison of learning types

| Learning type | Data or feedback | Main purpose | Example |
|---|---|---|---|
| Supervised learning | Examples with known labels or target values | Predict a category or value | Classifying emails as spam or not spam |
| Unsupervised learning | Data without predefined target labels | Discover patterns or groupings | Grouping customers by purchase behaviour |
| Reinforcement learning | Feedback from actions in an environment | Learn a strategy through interaction | Learning to play a game |

---

## 2.7 Classification and Regression

Two common supervised learning tasks are classification and regression.

### Classification

Classification predicts a category or class.

Examples include:

- Classifying an email as spam or not spam.
- Categorising a photograph as a cat, dog, or bird.
- Classifying a transaction as potentially fraudulent or not flagged.

A classification model may produce a probability or confidence score for each category, depending on the model and its design.

A prediction score should not automatically be interpreted as a guarantee that the predicted category is correct.

### Regression

Regression predicts a numerical value.

Examples include:

- Estimating the price of a house.
- Predicting electricity demand.
- Estimating travel time from relevant information.

Regression predictions are estimates and may differ from actual values.

### Compare the tasks

Imagine that a school wants to use student attendance data.

- Predicting whether a student is at risk of missing a required attendance threshold is a **classification** task if the target is a category.
- Predicting the number of days a student may be absent is a **regression** task if the target is a numerical value.

The appropriate task depends on the question the model is intended to answer.

---

## 2.8 Training, Validation, and Test Data

To understand whether a model can generalise to new situations, machine learning projects often separate data into training, validation, and test sets.

### Training data

Training data is used by the learning algorithm to fit the model.

### Validation data

Validation data is used during model development to compare approaches or adjust settings.

Not every small project requires a separate validation set, but it is useful when making repeated choices about model configuration.

### Test data

Test data is reserved for evaluating the final model after development choices have been made.

The test set should represent the situations in which the model is expected to be used, as closely as practical.

### Example

Suppose a project has 1,000 labelled examples.

A possible split could be:

- 700 examples for training.
- 150 examples for validation.
- 150 examples for testing.

This is only an illustration. The best split depends on the amount and type of data, the learning method, and the task.

### Why separate the data?

If a model is evaluated only on examples it has already seen during training, its performance may appear better than it will be on new examples.

Using separate evaluation data helps reveal whether the model has learned patterns that generalise beyond the training examples.

**Important:** Data leakage occurs when information that would not legitimately be available at prediction time influences model training or evaluation. Leakage can make performance appear unrealistically strong.

---

## 2.9 Evaluating a Machine Learning Model

A model should be evaluated according to the purpose of the task. No single measurement is suitable for every situation.

### Accuracy

Accuracy is the proportion of predictions that are correct.

For example, if a model correctly classifies 90 out of 100 examples, its accuracy is 90%.

However, accuracy alone can be misleading when one category is much more common than another.

Imagine a dataset in which 95% of transactions are legitimate. A model that always predicts “legitimate” would have 95% accuracy, yet it would fail to identify any fraudulent transactions.

### Precision

Precision measures the proportion of positive predictions that are actually positive.

For a fraud-detection model, precision helps answer:

**Of the transactions flagged as potentially fraudulent, how many were actually fraudulent?**

### Recall

Recall measures the proportion of actual positive cases that the model correctly identifies.

For fraud detection, recall helps answer:

**Of all fraudulent transactions, how many did the model identify?**

### Why the distinction matters

A system that flags too many legitimate transactions may inconvenience customers. A system that misses too many fraudulent transactions may fail to prevent losses.

The appropriate balance depends on the costs and consequences of different errors.

Other evaluation methods include F1 score, mean absolute error, and root mean squared error. The appropriate metric depends on whether the task is classification or regression and on the needs of the application.

### Evaluation checklist

When reviewing a model, ask:

1. What task is the model intended to perform?
2. What data was used for testing?
3. Which evaluation measures were selected, and why?
4. What kinds of mistakes does the model make?
5. Could its errors disproportionately affect particular people or groups?
6. Is its performance good enough for the intended use?

A model should not be considered reliable simply because it produces a high score on one metric.

---

## 2.10 Understanding Overfitting

Overfitting occurs when a model learns patterns that fit its training data very closely but does not perform well on new data.

A model may learn noise, accidental relationships, or details specific to the training examples instead of patterns that generalise.

### Example

Imagine that a model is trained to identify dogs using photographs. Most training photographs show dogs outdoors on grass.

If the model relies heavily on the background instead of learning features that distinguish dogs, it may perform well on similar training photographs but poorly on photographs of dogs indoors.

The model has learned a misleading relationship between the background and the target category.

### How can overfitting be reduced?

Possible approaches include:

- Collecting more representative training data.
- Using suitable validation data to guide model selection.
- Reducing unnecessary model complexity.
- Applying regularisation techniques where appropriate.
- Removing data leakage.
- Testing the model on data that reflects the intended real-world use.

These approaches can help, but none guarantees that a model will perform well in every new situation.

### Generalisation

Generalisation describes how well a model performs on new examples beyond the data used to train it.

Good generalisation is important because a useful model must work on relevant new cases, not just memorise its training examples.

---

## 2.11 Data Quality and Bias

Machine learning models depend on the data used to develop them. Poor-quality or unrepresentative data can lead to unreliable predictions.

### Common data-quality problems

**Missing data:** Some records lack important information.

**Incorrect data:** Records contain mistakes or inaccurate measurements.

**Duplicate data:** The same record appears more than once and may distort the learning process.

**Unrepresentative data:** The dataset does not adequately represent the people, situations, or environments where the model will be used.

**Outdated data:** Historical patterns may no longer reflect current conditions.

### What is bias in machine learning?

In this context, bias can refer to systematic patterns in data, model behaviour, or decision-making that produce unfair or distorted outcomes.

For example, suppose a system is designed to help screen job applications. If its training data reflects historical hiring practices that disadvantaged certain groups, the model may reproduce or reinforce those patterns.

This does not mean that every dataset produces unfair outcomes, but it shows why data and model behaviour need to be examined carefully.

### How can risks be reduced?

Practical measures include:

1. Checking the source and quality of the data.
2. Examining whether relevant groups are adequately represented.
3. Evaluating performance across appropriate groups.
4. Investigating patterns in errors and unexpected outcomes.
5. Protecting personal information.
6. Involving people with relevant knowledge in reviewing the system.
7. Monitoring the model after deployment.

Fairness cannot always be measured by one simple metric. Appropriate evaluation depends on the application, affected people, and relevant legal and ethical requirements.

---

## 2.12 Practical Learning Activity: Classify the Machine Learning Task

**Estimated time:** 10 minutes

### Purpose

Apply the concepts of learning types, classification, and regression to everyday scenarios.

### Instructions

Read each scenario. Identify the most suitable answer using the concepts introduced in this chapter.

| Scenario | Question |
|---|---|
| A. Email filtering | A system learns from emails labelled “Spam” and “Not spam” to classify new emails. |
| B. Customer grouping | A retailer wants to discover groups of customers with similar purchasing patterns, without predefined group labels. |
| C. House-price prediction | A model uses property features to estimate the selling price of a house. |
| D. Game-playing agent | An agent learns a strategy by taking actions in a game and receiving rewards or penalties. |
| E. Image classification | A model predicts whether a photograph contains a cat, a dog, or a bird. |

For each scenario, answer:

1. Which type of machine learning is most appropriate: supervised, unsupervised, or reinforcement learning?
2. If the task uses supervised learning, is it classification or regression?
3. What information would you need to evaluate whether the system works well?
4. Identify one possible limitation or risk.

### Answer guide

**A. Email filtering**

- Learning type: Supervised learning.
- Task: Classification.
- Evaluation: Examine appropriate measures such as precision, recall, and accuracy using separate test data.
- Possible limitation: Some legitimate emails may be incorrectly flagged as spam.

**B. Customer grouping**

- Learning type: Unsupervised learning.
- Task: Clustering or grouping.
- Evaluation: Examine whether the groups are meaningful, stable, and useful for the intended purpose.
- Possible limitation: The discovered groups may not represent meaningful customer differences.

**C. House-price prediction**

- Learning type: Supervised learning.
- Task: Regression.
- Evaluation: Compare predicted prices with actual prices on suitable test data using regression metrics.
- Possible limitation: Prices may change with market conditions, and historical data may not represent the current market.

**D. Game-playing agent**

- Learning type: Reinforcement learning.
- Task: Learning a strategy through interaction and reward feedback.
- Evaluation: Test performance across multiple games or scenarios.
- Possible limitation: The agent may perform poorly in situations different from those experienced during training.

**E. Image classification**

- Learning type: Supervised learning, assuming the model is trained using labelled images.
- Task: Classification.
- Evaluation: Measure classification performance on a suitable test dataset and investigate errors across relevant image conditions.
- Possible limitation: Performance may decline on images that differ substantially from the training data.

### Reflection

Which scenario might require the greatest human oversight before its predictions are used to make important decisions? Explain your answer.

There may be more than one reasonable response. Your explanation should consider the consequences of errors and the people affected.

---

## 2.13 Knowledge Check

Answer the following questions before reading the answer key.

### Question 1

What is machine learning?

A. A method of storing files on a computer.  
B. An area of AI in which systems learn patterns from data.  
C. A programming language used only for websites.  
D. A method that guarantees every prediction is correct.

### Question 2

What is a feature in machine learning?

A. An input characteristic used by a model.  
B. The final report written by a developer.  
C. A guaranteed correct prediction.  
D. A type of computer hardware.

### Question 3

A model learns from examples labelled “Approved” and “Rejected” to predict the category of new applications. Which learning type is this?

A. Unsupervised learning.  
B. Reinforcement learning.  
C. Supervised learning.  
D. Manual data entry.

### Question 4

A model estimates the price of a house. Is this generally a classification or regression task?

A. Classification.  
B. Regression.  
C. Clustering.  
D. Reinforcement learning.

### Question 5

Why should test data be kept separate from training data?

A. To guarantee that the model never makes a mistake.  
B. To make the dataset smaller without any other purpose.  
C. To help evaluate how the model performs on examples it did not use for training.  
D. To remove the need for data preparation.

### Question 6

What is overfitting?

A. When a model performs well on training data but poorly on new data.  
B. When a model uses no data.  
C. When a dataset contains only numerical values.  
D. When a computer runs out of storage space.

### Question 7

Why can high accuracy be misleading when evaluating a model?

A. Accuracy cannot be calculated for machine learning.  
B. A model may perform well on the majority category while failing to identify important minority cases.  
C. Accuracy always measures fairness.  
D. High accuracy proves that the data is unbiased.

### Question 8

Which action can help reduce risks caused by unrepresentative data?

A. Ignore model errors.  
B. Evaluate model performance across relevant groups and investigate differences.  
C. Use only the training data for evaluation.  
D. Assume that more data automatically removes every bias.

### Question 9

A system groups documents according to similarities without being given predefined category labels. Which learning type is most relevant?

A. Supervised learning.  
B. Unsupervised learning.  
C. Reinforcement learning.  
D. Regression only.

### Question 10

Why should a deployed machine learning model be monitored?

A. Because its performance and the conditions in which it operates can change over time.  
B. Because monitoring guarantees perfect predictions.  
C. Because monitoring removes the need for human judgement.  
D. Because models never require updates.

---

## 2.14 Answer Key and Explanations

| Question | Correct answer | Explanation |
|---|---|---|
| 1 | B | Machine learning uses data to learn patterns that can support predictions or other tasks. |
| 2 | A | A feature is an input characteristic used by a model. |
| 3 | C | Supervised learning uses examples with known labels or target values. |
| 4 | B | House prices are numerical values, so predicting them is generally a regression task. |
| 5 | C | Separate test data helps estimate how well the model performs on unseen examples. |
| 6 | A | Overfitting occurs when a model fits training data closely but does not generalise well. |
| 7 | B | A model can achieve high accuracy by predicting the majority category while missing important minority cases. |
| 8 | B | Examining performance across relevant groups can reveal issues that need further investigation. |
| 9 | B | Unsupervised learning can identify similarities and groupings without predefined target labels. |
| 10 | A | Data and real-world conditions can change, affecting the model's usefulness and reliability. |

### Suggested self-assessment

- **9–10 correct:** You demonstrate a strong understanding of the chapter's key concepts.
- **7–8 correct:** You understand most of the material. Review any concepts you missed.
- **5–6 correct:** Revisit the learning types, evaluation methods, and overfitting sections.
- **0–4 correct:** Review the chapter and repeat the knowledge check before continuing.

This self-assessment is intended to guide revision rather than serve as a formal grade.

---

## 2.15 Key Terms Glossary

| Term | Definition |
|---|---|
| Algorithm | A procedure or set of methods used to learn patterns or solve a problem. |
| Artificial intelligence (AI) | The broader field of developing systems that perform tasks associated with capabilities such as reasoning, perception, prediction, and language processing. |
| Classification | A task that predicts a category or class. |
| Data | Information used to develop or operate a system. |
| Data leakage | The use of information during training or evaluation that would not legitimately be available for the intended prediction task. |
| Dataset | An organised collection of data. |
| Deep learning | A type of machine learning that uses neural networks with multiple layers. |
| Evaluation | The process of measuring model performance. |
| Feature | An input characteristic used by a model. |
| Generalisation | The ability of a model to perform well on relevant new examples. |
| Label | A known target or category used in supervised learning. |
| Machine learning (ML) | An area of AI in which systems learn patterns from data. |
| Model | A learned representation of patterns used to produce predictions or support decisions. |
| Overfitting | When a model fits training data closely but performs poorly on new data. |
| Prediction | An output produced by a model for a given input. |
| Regression | A task that predicts a numerical value. |
| Reinforcement learning | A learning approach in which an agent learns through actions and feedback from an environment. |
| Supervised learning | A learning approach that uses examples with known labels or target values. |
| Test data | Data reserved to evaluate a model's performance after development. |
| Training data | Data used by a learning algorithm to fit a model. |
| Unsupervised learning | A learning approach that identifies patterns or structure in data without predefined target labels. |
| Validation data | Data used during development to compare models or adjust settings. |

---

## 2.16 Chapter Summary

Machine learning is an important area of AI that enables systems to learn patterns from data.

In this chapter, you learned that:

- Machine learning models use data to learn patterns and produce predictions.
- Features describe the inputs used by a model, while labels provide target answers in supervised learning.
- Supervised learning uses labelled examples, unsupervised learning explores data without predefined target labels, and reinforcement learning uses feedback from actions.
- Classification predicts categories, while regression predicts numerical values.
- Training, validation, and test data serve different purposes during model development.
- Evaluation measures must be selected according to the task and consequences of errors.
- Overfitting occurs when a model performs well on training data but fails to generalise to new examples.
- Poor-quality or unrepresentative data can lead to unreliable or unfair outcomes.
- Machine learning systems should be evaluated and monitored rather than assumed to be correct.

Understanding these principles provides a foundation for studying generative AI, real-world AI applications, and responsible AI use in the following chapters.

---

## 2.17 References and Further Reading

The following resources provide further information about machine learning and model evaluation.

1. **Google for Developers.** *Machine Learning Crash Course.*  
   https://developers.google.com/machine-learning/crash-course  
   An educational resource covering machine learning concepts, data, models, and evaluation.

2. **Google for Developers.** *Classification: Accuracy, Recall, Precision, and Related Metrics.*  
   https://developers.google.com/machine-learning/crash-course/classification/accuracy-precision-recall  
   An introduction to common evaluation measures for classification tasks.

3. **scikit-learn.** *Supervised learning.*  
   https://scikit-learn.org/stable/supervised_learning.html  
   Documentation explaining supervised learning methods and applications.

4. **scikit-learn.** *Unsupervised learning.*  
   https://scikit-learn.org/stable/unsupervised_learning.html  
   Documentation introducing methods for identifying patterns in data without predefined target labels.

5. **IBM.** *What is machine learning?*  
   https://www.ibm.com/think/topics/machine-learning  
   An overview of machine learning concepts and applications.

**Reference note:** These resources are provided for further study. Check the linked pages for their current content and cite the specific sources you consult if you adapt material for a submitted academic assignment.

---

## 2.18 Chapter Completion Checklist

Before considering this chapter complete, confirm that:

- [x] All learning objectives are addressed in the chapter.
- [x] Key concepts are explained using beginner-friendly language.
- [x] Examples illustrate the difference between learning types.
- [x] Classification and regression are clearly distinguished.
- [x] Training, validation, and test data are explained.
- [x] Model evaluation and overfitting are covered.
- [x] Data quality and bias are discussed.
- [x] The practical activity has clear instructions and an answer guide.
- [x] Knowledge-check questions include answers and explanations.
- [x] The glossary and summary are complete.
- [ ] References have been checked to confirm they are accessible and relevant.
- [x] The chapter's estimated learning time matches the module outline.
- [ ] Markdown tables, headings, and links have been checked to ensure they render correctly.

**End of Chapter 2**
