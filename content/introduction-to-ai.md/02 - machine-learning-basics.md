# Topic 2: Machine Learning Basics

**Author:** Michelle Kalyani

## 1. What Is Machine Learning?

Machine learning (ML) is a branch of artificial intelligence (AI) that allows computers to learn patterns from data and use those patterns to make predictions or decisions [1, 4].

Instead of programming every rule manually, developers train a machine learning model using examples.

**Example: Spam Email Detection**

A spam filter learns from emails labeled as either "spam" or "not spam." After training, it can use what it has learned to predict whether a new email is spam.

## 2. The Machine Learning Process

Machine learning usually follows these steps [2, 3]:

1. **Collect data:** Gather information related to the problem.
2. **Prepare the data:** Check for errors, remove unnecessary information, and organize the data.
3. **Train the model:** Use the prepared data to help the model learn patterns.
4. **Test the model:** Evaluate how well the model works on data it has not seen during training.
5. **Deploy and monitor:** Put the model into use and check its performance over time.

The quality and relevance of the data can strongly affect how well a model performs. Testing is also important because a model that performs well during training may not work well with new data [3].

## 3. Types of Machine Learning

There are three commonly taught types of machine learning: supervised learning, unsupervised learning, and reinforcement learning [1, 4].

### 3.1 Supervised Learning

**Supervised learning** trains a model using labeled data. Labeled data contains examples along with their correct answers or categories [1].

**Example:** A spam filter is trained using emails labeled "spam" or "not spam." It learns patterns associated with each category and uses them to classify new emails.

**Key idea:** The model learns from examples that include the correct answers.

### 3.2 Unsupervised Learning

**Unsupervised learning** uses data without preassigned answers or labels. The model looks for patterns, similarities, or groups in the data [1].

**Example:** A business analyzes customer purchasing habits and groups customers with similar shopping patterns. The groups can help the business understand its customers.

**Key idea:** The model searches for patterns without being given the correct answer for each example.

### 3.3 Reinforcement Learning

**Reinforcement learning** involves an agent learning through interaction with an environment. The agent receives feedback, often in the form of rewards or penalties, and learns which actions are more effective over time [1, 4].

**Example:** An agent learns to play a simple game. It receives rewards for successful actions and learns to avoid actions that lead to poor results.

**Key idea:** The agent learns by taking actions and receiving feedback.

### Comparing the Three Types

| Type | How it learns | Example |
|---|---|---|
| Supervised learning | Learns from labeled examples | Detecting spam emails |
| Unsupervised learning | Finds patterns in unlabeled data | Grouping customers |
| Reinforcement learning | Learns through actions and feedback | Learning to play a game |

## 4. Classification and Regression

Machine learning models can be used for different kinds of predictions. Two common tasks are classification and regression [1, 2].

### 4.1 Classification

**Classification** predicts a category or class [1].

Examples:
- Deciding whether an email is spam or not spam.
- Classifying an image as a cat or a dog.
- Predicting whether a transaction may be fraudulent.

**Remember:** Classification predicts a category.

### 4.2 Regression

**Regression** predicts a numerical value [1, 2].

Examples:
- Estimating the price of a house.
- Predicting tomorrow's temperature.
- Estimating how many minutes a journey may take.

**Remember:** Regression predicts a number.

| Classification | Regression |
|---|---|
| Predicts a category | Predicts a numerical value |
| Example: Spam or not spam | Example: A journey will take 25 minutes |

## 5. What Is Overfitting?

**Overfitting** occurs when a model learns the training data too closely, including details or noise that do not help it perform well on new data [3].

As a result, the model may perform very well on its training examples but poorly on unfamiliar examples.

**Example:** A student memorizes the answers to a set of practice questions but does not understand the underlying concepts. When the exam contains different questions, the student struggles to answer them.

Similarly, an overfitted model may struggle when it encounters data that differs from its training examples.

Testing a model on unseen data helps reveal whether it can perform well beyond the examples it has already learned from [3].

## 6. Key Takeaways

- Machine learning is a branch of AI that learns patterns from data.
- The main steps include collecting data, preparing it, training a model, testing it, and monitoring its performance.
- Supervised learning learns from labeled examples.
- Unsupervised learning finds patterns in data without given labels.
- Reinforcement learning learns through actions and feedback.
- Classification predicts categories, while regression predicts numerical values.
- Overfitting occurs when a model performs well on training data but poorly on new data.

## 7. Review Questions

Test your understanding of the concepts in this lesson.

1. What is machine learning, and how does it differ from manually programming every rule?
2. What are the main steps in the machine learning process?
3. How do supervised learning and unsupervised learning differ?
4. Which type of machine learning uses actions and feedback to learn?
5. Explain the difference between classification and regression. Give one example of each.
6. What is overfitting, and why can it cause problems?
7. Why should a machine learning model be tested using data it has not seen during training?

## 8. References

1. Google for Developers. (n.d.). *What is machine learning?*  
   https://developers.google.com/machine-learning/intro-to-ml/what-is-ml

2. Google for Developers. (n.d.). *Machine Learning Crash Course.*  
   https://developers.google.com/machine-learning/crash-course/

3. Google for Developers. (2025, December 3). *Datasets, generalization, and overfitting.*  
   https://developers.google.com/machine-learning/crash-course/overfitting

4. Bergmann, D. (2026, October 2). *What is machine learning?* IBM.  
   https://www.ibm.com/think/topics/machine-learning
