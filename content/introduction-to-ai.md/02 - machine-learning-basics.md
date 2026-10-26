# Chapter 2: Machine Learning Basics

**Project:** Curious Mind — Introduction to Artificial Intelligence  
**Author:** Michelle Kalyani  
**Chapter:** 2  
**Estimated study time:** 25–35 minutes  
**Prerequisite:** Chapter 1 — What Is Artificial Intelligence?

---

## 2.1 Introduction

Artificial intelligence (AI) enables computers to perform tasks that typically require human intelligence. One important area of AI is **machine learning (ML)**.

Machine learning allows computers to identify patterns in data and use those patterns to make predictions or decisions. Instead of manually writing every rule, developers provide data and select a learning method that allows a model to learn patterns relevant to a task [1].

Machine learning is used in many everyday applications, including email spam filters, recommendation systems, image recognition, and demand forecasting.

For example, an email service can use machine learning to identify patterns associated with spam messages. After learning from examples, the system can estimate whether a new email is likely to be spam.

However, machine learning is not perfect. A model's performance depends on factors such as the quality of its data, the learning method, and how well it handles new situations.

This chapter introduces the fundamental concepts needed to understand how machine learning works.

### Learning objectives

By the end of this chapter, learners should be able to:

1. Define machine learning and explain its relationship to artificial intelligence.
2. Describe the main stages of a typical machine learning workflow.
3. Distinguish supervised, unsupervised, and reinforcement learning.
4. Explain the difference between classification and regression.
5. Describe training data, test data, and model evaluation.
6. Explain overfitting and why it can reduce a model's performance on new data.
7. Identify basic data-quality, fairness, privacy, and reliability concerns.

---

## 2.2 What Is Machine Learning?

**Machine learning is a field of AI in which computer systems use data to learn patterns that support predictions, decisions, or other tasks.** [1]

In traditional rule-based programming, a developer writes explicit instructions for a system to follow.

In machine learning, a developer selects a suitable learning method and provides relevant data. A learning algorithm uses that data to produce a model that can make predictions on new inputs.

### Example: Spam email detection

Imagine that an email service needs to identify unwanted messages.

A traditional rule-based system might mark an email as spam whenever it contains a particular word. However, spammers can change their wording, making simple rules less effective.

A machine learning approach can use examples of emails labelled as spam or not spam. During training, the learning algorithm identifies patterns associated with each category.

When a new email arrives, the trained model uses the patterns it learned to predict whether the email is likely to be spam.

The prediction is not guaranteed to be correct. Some legitimate emails may be incorrectly flagged, while some spam messages may be missed.

### Key terms

|
