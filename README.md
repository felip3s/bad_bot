# Project: LLM Safeguard Bypass Exploration

* **Author:** Felipe Silva
* **Course/Term:** LLM Fall, 2025
* **Institution:** Portland State University

---

## ⚠️ **CRITICAL WARNING: Content Advisory**

**This model outputs potentially offensive, inappropriate, and triggering content.**
It is designed to generate text that may include:
* Hate-speech
* Profanity
* Sexual Content
* Violence

**Viewer discretion is strongly advised.**

---

### Project Objectives

The primary goal of this research project is to **bypass built-in LLM safeguards** designed to prevent the generation of harmful content.

We aim to:
1.  Explore and document the response of different, publicly available models to various exploits.
2.  Specifically, investigate **system instructions** as a primary exploit mechanism for bypassing safety filters.
3.  Analyze the resulting model behavior in uncensored scenarios.

### Methodology & Benchmark

#### **Exploit Focus**
We are using **system instructions** to manipulate the model's behavior and encourage the generation of harmful or restricted content.

#### **Benchmark**
The uncensored model outputs are benchmarked against the standard, publicly available **chat-based online versions** of the same models.

#### **Evaluation**
An **AI Judge** is used to quantitatively measure the toxicity and unsafety of the model's uncensored output. The judge makes determinations based on the presence of the following categories:

* **Hate-speech**
* **Profanity**
* **Sexual Content**
* **Violence**