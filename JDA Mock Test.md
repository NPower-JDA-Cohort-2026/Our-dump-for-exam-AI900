---
tags: [jda, ai-fundamentals, azure, mock-test]
source:
  - "Introduction to AI concepts (Microsoft Learn)"
  - "Get started with AI in Azure (Microsoft Learn)"
created: 2026-06-12
questions: 30
---

# JDA Mock Test — AI Fundamentals & AI in Azure

**Instructions:** 30 multiple-choice questions. Pick one answer per question unless stated otherwise. Answer key is at the bottom — don't peek until you're done!

- Part 1 (Q1–18): Introduction to AI concepts
- Part 2 (Q19–30): Get started with AI in Azure

---

## Part 1 — Introduction to AI Concepts

**Q1.** Which of the following best describes generative AI?
- A) AI that classifies data into predefined categories
- B) AI that creates original content such as text, images, or code based on a prompt
- C) AI that only retrieves existing documents from a database
- D) AI that controls physical robots

**Q2.** What is the input that a user provides to a generative AI model called?
- A) A token
- B) A parameter
- C) A prompt
- D) A query string

**Q3.** Generative AI models that work with multiple types of data (text, images, audio) are described as:
- A) Multimodal
- B) Multithreaded
- C) Multitenant
- D) Multivariate

**Q4.** What distinguishes an AI **agent** from a simple chat-based generative AI assistant?
- A) Agents can only answer questions about documents
- B) Agents can reason over inputs, use tools, and take actions to automate tasks with little or no human intervention
- C) Agents are always cheaper to run
- D) Agents don't use language models

**Q5.** A language model represents words or pieces of words as numeric units called:
- A) Pixels
- B) Vectors only
- C) Tokens
- D) Bits

**Q6.** Which AI workload determines whether a customer review expresses a positive or negative opinion?
- A) Speech synthesis
- B) Sentiment analysis
- C) Object detection
- D) Image classification

**Q7.** Identifying names of people, places, and organizations mentioned in a document is an example of:
- A) Entity recognition
- B) Text translation
- C) Key phrase extraction... of audio
- D) Optical character recognition

**Q8.** Converting spoken audio into written text is called:
- A) Speech synthesis
- B) Text-to-speech
- C) Speech recognition (speech-to-text)
- D) Translation

**Q9.** Converting written text into spoken audio is called:
- A) Speech recognition
- B) Speech synthesis (text-to-speech)
- C) Transcription
- D) Tokenization

**Q10.** An app needs to identify *what* objects appear in an image **and** *where* they are located (with bounding boxes). Which computer vision task is this?
- A) Image classification
- B) Object detection
- C) Facial recognition
- D) OCR

**Q11.** An app assigns a single label ("cat" or "dog") to an entire photo. Which computer vision task is this?
- A) Image classification
- B) Object detection
- C) Semantic segmentation
- D) Image generation

**Q12.** Which technology extracts printed or handwritten text from scanned images or photos?
- A) Entity recognition
- B) Optical character recognition (OCR)
- C) Speech recognition
- D) Image classification

**Q13.** Automatically pulling fields like totals, dates, and vendor names from scanned invoices or forms is an example of which workload?
- A) Information extraction / document intelligence
- B) Speech synthesis
- C) Image generation
- D) Reinforcement learning

**Q14.** A bank's loan-approval AI model performs noticeably worse for one demographic group because of biased training data. Which responsible AI principle is violated?
- A) Transparency
- B) Fairness
- C) Reliability and safety
- D) Privacy and security

**Q15.** Which responsible AI principle states that AI systems should perform consistently and handle unexpected conditions without causing harm (for example, a self-driving car system)?
- A) Inclusiveness
- B) Accountability
- C) Reliability and safety
- D) Fairness

**Q16.** Which responsible AI principle is about helping people understand how an AI system works, its capabilities, and its limitations?
- A) Transparency
- B) Privacy and security
- C) Fairness
- D) Inclusiveness

**Q17.** Which responsible AI principle says that the people who design and deploy AI systems must answer for how those systems operate?
- A) Transparency
- B) Accountability
- C) Reliability and safety
- D) Inclusiveness

**Q18.** Designing AI solutions so they empower and engage everyone, including people with disabilities, reflects which responsible AI principle?
- A) Fairness
- B) Inclusiveness
- C) Accountability
- D) Transparency

---

## Part 2 — Get Started with AI in Azure

**Q19.** What is Microsoft Azure?
- A) A desktop operating system
- B) Microsoft's cloud computing platform offering scalable services over the internet
- C) A programming language
- D) A database file format

**Q20.** Microsoft Foundry is best described as:
- A) An open-source Python library
- B) A unified, enterprise-grade PaaS for building, deploying, and managing AI applications and agents
- C) A hardware device for training models
- D) A replacement for the Azure portal

**Q21.** Which of the following is NOT one of the core capability areas of Microsoft Foundry?
- A) Models
- B) Agents
- C) Tools
- D) Spreadsheets

**Q22.** Where do developers browse, evaluate, and deploy first-party, third-party, and open-source models in Foundry?
- A) The model catalog
- B) The Azure Marketplace only
- C) GitHub
- D) Foundry IQ

**Q23.** What is Foundry IQ?
- A) A pricing calculator
- B) A permission-aware, multi-source knowledge layer that grounds agents in an organization's own data
- C) An IQ test for models
- D) A monitoring dashboard

**Q24.** What is the relationship between a Foundry **resource** and a Foundry **project**?
- A) They are the same thing
- B) A project contains many resources
- C) A resource is the Azure resource providing platform capabilities; a project is a workspace inside it where you build apps, agents, and evaluations
- D) Resources are free, projects are paid

**Q25.** In the Foundry portal, what is the Playground used for?
- A) Writing production code
- B) Experimenting with a deployed model — writing prompts, testing responses, and configuring parameters
- C) Managing billing
- D) Creating Azure subscriptions

**Q26.** In a client–server AI application, which task belongs to the **server** (the model deployment)?
- A) Presenting the user interface
- B) Collecting user input
- C) Running inference on the model and returning the generated output
- D) Displaying results on screen

**Q27.** What is an API endpoint in the context of Foundry?
- A) A physical network cable
- B) A unique HTTP address that serves as the entry point client applications use to access the service
- C) The end of a project's lifecycle
- D) A type of database

**Q28.** How are Foundry endpoints kept secure?
- A) They are hidden from the internet entirely
- B) Applications must present a valid API key or a Microsoft Entra ID token
- C) Only Microsoft employees can call them
- D) They only accept requests on weekends

**Q29.** REST requests sent to a Foundry model endpoint typically contain a body formatted in:
- A) XML
- B) CSV
- C) JSON
- D) Plain binary

**Q30.** Why do most developers use an SDK instead of calling the REST interface directly?
- A) REST interfaces are deprecated
- B) SDKs abstract the REST calls into code libraries for languages like Python, JavaScript, or C#, making development easier
- C) SDKs are required by law
- D) REST cannot return JSON

---

## ✅ Answer Key

| Q | Ans | Q | Ans | Q | Ans |
|---|-----|---|-----|---|-----|
| 1 | B | 11 | A | 21 | D |
| 2 | C | 12 | B | 22 | A |
| 3 | A | 13 | A | 23 | B |
| 4 | B | 14 | B | 24 | C |
| 5 | C | 15 | C | 25 | B |
| 6 | B | 16 | A | 26 | C |
| 7 | A | 17 | B | 27 | B |
| 8 | C | 18 | B | 28 | B |
| 9 | B | 19 | B | 29 | C |
| 10 | B | 20 | B | 30 | B |

---

## Scoring

- **27–30** → Excellent, ready for the module assessments
- **21–26** → Good, review the questions you missed
- **Below 21** → Re-read the weak units, then retake the test

## Sources

- [Introduction to AI concepts](https://learn.microsoft.com/en-us/training/modules/get-started-ai-fundamentals/)
- [Get started with AI in Azure](https://learn.microsoft.com/en-us/training/modules/get-started-with-ai-in-azure/)

*Tip: track your attempts here:*

| Date | Score | Notes |
|------|-------|-------|
|      | 26/30 |       |
