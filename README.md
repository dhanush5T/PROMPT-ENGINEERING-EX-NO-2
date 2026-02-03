# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT

## **INTRODUCTION**

With the rapid growth of **Artificial Intelligence (AI)**, large language models are increasingly used in educational platforms for content summarization. Summarization helps students quickly grasp complex topics without reading lengthy technical documents. However, the quality of AI-generated summaries depends heavily on **how prompts are framed** and **which AI platform is used**.

Different prompting techniques guide the AI in different ways. Similarly, AI platforms differ in architecture, training data, and response style. This experiment explores how these factors influence the **quality, clarity, and usefulness** of summaries generated for academic purposes.

## **PROBLEM STATEMENT**

Educational platforms require summaries that are:

* Technically accurate
* Easy to understand
* Well-structured
* Suitable for undergraduate students

The challenge is to identify:

* The **best prompting technique**
* The **most suitable AI platform**
  for summarizing a **500-word technical article on “The Basics of Blockchain Technology.”**

## **DESCRIPTION OF THE TASK**

A technical article explaining:

* Blockchain definition
* Working principle
* Key features (decentralization, immutability, transparency)
* Applications

was summarized using:

* **Four prompting techniques**
* **Four AI platforms**

The generated summaries were evaluated using predefined performance metrics.


## **PROMPTING TECHNIQUES – DETAILED EXPLANATION**

### **1. Zero-Shot Prompting**

In zero-shot prompting, the AI is given **only the task** without any additional guidance or examples.

**Characteristics:**

* Simplest form of prompting
* No context or style guidance
* Fast response generation

**Outcome:**

* Summary was brief but lacked depth
* Some technical concepts were oversimplified
* Less suitable for academic learning

---

### **2. Few-Shot Prompting**

Few-shot prompting provides the AI with **one or more examples** before asking it to perform the task.

**Characteristics:**

* AI learns structure and tone from examples
* Improves consistency and formatting

**Outcome:**

* More organized summaries
* Better use of technical terminology
* Slightly increased response time


### **3. Chain-of-Thought Prompting**

This technique instructs the AI to **think step-by-step** before producing the final answer.

**Characteristics:**

* Encourages logical reasoning
* Enhances coherence and clarity

**Outcome:**

* Well-structured summaries
* Clear explanation of blockchain concepts
* Slightly longer processing time


### **4. Role-Based Prompting**

In role-based prompting, the AI is assigned a **specific role** to shape its response.

**Characteristics:**

* Tailors language and depth
* Focuses on target audience

**Outcome:**

* Highly student-friendly summaries
* Balanced technical depth and simplicity
* Best overall learning experience

## **AI PLATFORMS USED – OVERVIEW**

### **ChatGPT**

* Strong contextual understanding
* Excellent educational explanations
* Adapts well to role-based and reasoning prompts

### **Gemini**

* Very fast response generation
* Good surface-level summaries
* Less detailed technical explanation

### **Claude**

* Highly coherent and structured output
* Excellent reasoning ability
* Slightly slower responses

### **Copilot**

* Optimized for productivity tasks
* Suitable for quick summaries
* Limited depth in academic explanation

## **EVALUATION CRITERIA**

| Parameter           | Description                                   |
| ------------------- | --------------------------------------------- |
| **Accuracy**        | Correct representation of blockchain concepts |
| **Coherence**       | Logical flow and organization                 |
| **Simplicity**      | Ease of understanding for undergraduates      |
| **Speed**           | Time taken to generate response               |
| **User Experience** | Readability and usefulness                    |


## **COMPARATIVE ANALYSIS**

| Platform | Best Technique   | Performance Summary                            |
| -------- | ---------------- | ---------------------------------------------- |
| ChatGPT  | Role-based + CoT | Best balance of clarity, depth, and simplicity |
| Gemini   | Few-shot         | Fast but less detailed                         |
| Claude   | Chain-of-Thought | Very accurate and structured                   |
| Copilot  | Zero-shot        | Quick but basic                                |


## **RESULTS**

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/383c2c26-36b0-4250-8e29-a62d31617b18" />






* **Role-based prompting** produced the most effective summaries for educational use.
* **Chain-of-thought prompting** improved conceptual clarity.
* **ChatGPT** provided the most consistent high-quality summaries.
* **Claude** was best for logical and structured content.
* **Zero-shot prompting**, though fast, was least effective for technical learning.



## **CONCLUSION**

This experiment demonstrates that **prompt engineering significantly impacts the quality of AI-generated summaries**. While all platforms can perform summarization, the **combination of Role-Based Prompting with ChatGPT** delivered the most accurate, coherent, simple, and student-friendly output.
Hence, careful selection of **prompting strategy and platform** is essential for effective AI-assisted education.

