---
tags: [jda, ai-900, mock-test, claude-generated]
source:
  - "All JDA Program notes, assessments, and Microsoft Learn AI-900 path"
created: 2026-06-18
questions: 30
goal: "Exam AI-900: Microsoft Azure AI Fundamentals"
---

# Mock Claude 2 — AI-900 Full Coverage Exam (Applied Scenarios)

**Instructions:** 30 questions, weighted toward scenario-based and applied reasoning (the style most likely to trip you up on the real exam). Covers AI workloads, Microsoft Foundry, Computer Vision, NLP, Document Intelligence, Speech, and Generative AI/Agents. Answer key and explanations are at the bottom.

Related: [[JDA Mock Test]] · [[JDA Mock Test 2]] · [[JDA Mock Test 3]] · [[Mock Claude 1]]

---

## Section A — AI Workloads, Foundry & Responsible AI (Q1–7)

**Q1. (Scenario)** A municipal government wants to deploy an AI chatbot to answer citizen questions about permits but is concerned that the bot's reasoning must be explainable to auditors. Which responsible AI principle is the PRIMARY concern here?
- A) Inclusiveness
- B) Transparency
- C) Performance optimization
- D) Cost efficiency

**Q2.** Which of the following best describes Microsoft Foundry's role in an organization's AI strategy?
- A) A unified platform for discovering, building, evaluating, and deploying AI models and agents
- B) A replacement for Azure Active Directory
- C) A tool exclusively for image editing
- D) A billing-only dashboard

**Q3.** In Microsoft Foundry, what is the relationship between a **resource** and a **project**?
- A) A project is the Azure-level container; a resource lives inside it
- B) A resource is the Azure-level container providing platform capabilities; a project is a workspace within it
- C) They are interchangeable terms for the same object
- D) A resource can only contain one model

**Q4. (Multiple Select — choose 2)** Which of the following are core capability areas commonly found in Microsoft Foundry? *(Select 2)*
- A) Model catalog and playgrounds
- B) Agent building and tools
- C) Physical server racking
- D) Manual invoice printing
- E) Spreadsheet macros

**Q5. (Scenario)** A nonprofit wants to analyze participant survey data and forecast program dropout risk. The solution must be secure, scalable, and manageable by a small, non-technical team across departments. What is the best approach?
- A) Build local ML models on each staff member's laptop
- B) Manually tag spreadsheets every week
- C) Use Microsoft Foundry to manage the AI lifecycle in a unified, governed platform
- D) Avoid AI entirely and use fixed business rules

**Q6.** Why is keeping a human in the loop important for high-impact AI-assisted decisions, such as loan approvals or medical diagnoses?
- A) It slows down the system unnecessarily
- B) It supports responsible AI practices like accountability and harm mitigation
- C) It is only required for marketing content
- D) It eliminates the need for model evaluation

**Q7.** What is the purpose of model evaluation and comparison tools in a platform like Foundry?
- A) To automatically reduce Azure billing
- B) To help teams choose the best-performing model for their use case based on documented metrics
- C) To replace the need for responsible AI review
- D) To encrypt model weights

---

## Section B — Computer Vision (Q8–12)

**Q8.** What kind of values does computer vision fundamentally analyze in an image?
- A) File metadata only
- B) Pixels
- C) File names
- D) Folder structure

**Q9.** In a convolutional neural network (CNN) used for image classification, what is the primary role of filters?
- A) To apply cosmetic visual effects
- B) To extract numeric features from the image for the neural network to learn from
- C) To compress the image file size
- D) To rename image files automatically

**Q10. (Scenario)** A warehouse wants a camera system that can tell them not just THAT there are boxes in a frame, but exactly HOW MANY boxes and WHERE each one is located in the image. Which capability is required?
- A) Image classification only
- B) Object detection
- C) Sentiment analysis
- D) Language detection

**Q11.** A Vision Transformer (ViT) is best described as:
- A) A tool that only applies visual filters to change image appearance
- B) A model that uses attention to process image patches and build contextual embeddings
- C) An agent that converts a language model into a vision model
- D) A compression algorithm for video files

**Q12.** Which of the following is the best description of a multimodal AI model?
- A) A model restricted to only one data type
- B) A model that can understand and work with more than one type of data, such as text and images together
- C) A model that only generates video
- D) A model that only runs on mobile devices

---

## Section C — NLP & Azure AI Language (Q13–20)

**Q13. (Scenario)** A retail analytics team wants to automatically classify thousands of overnight customer reviews into positive, neutral, or negative sentiment without needing real-time results. Which processing approach AND Azure capability combination fits best?
- A) Real-time streaming with Azure AI Vision
- B) Batch text analytics with Azure AI Language sentiment analysis
- C) Manual tagging with Excel
- D) Speech transcription with Azure AI Speech

**Q14.** Which technique strips word endings like "-ing", "-ed", and "-s" to reduce words to a common root, without guaranteeing the result is a valid dictionary word?
- A) Lemmatization
- B) Stemming
- C) Tokenization
- D) Parts of speech tagging

**Q15.** Why might "Banks" (a surname) and "banks" (financial institutions) need to be treated as distinct tokens in some NLP analyses?
- A) To reduce overall token count
- B) To preserve semantic distinctions between proper names and common nouns
- C) To improve storage efficiency
- D) To eliminate stop words faster

**Q16.** Which NLP feature identifies real-world entities such as people, organizations, and locations mentioned in unstructured text?
- A) Key phrase extraction
- B) Named Entity Recognition (NER)
- C) Token frequency analysis
- D) Text summarization

**Q17. (Multiple Select — choose 2)** Which of the following are TRUE about semantic (vector-based) language models compared to purely statistical methods? *(Select 2)*
- A) They understand word order and context better
- B) They always require less training data than statistical models
- C) Semantically similar words have vectors pointing in similar directions
- D) They eliminate all forms of model bias
- E) They process language without using any numeric representation

**Q18.** A model is asked to determine the sentiment of a sarcastic product review and gets it wrong, interpreting "Oh great, ANOTHER broken charger" as positive. What does this best illustrate?
- A) A tokenization failure
- B) A limitation in the model's language understanding
- C) A network latency issue
- D) A batching error in the pipeline

**Q19.** What is the primary goal of removing stop words like "the," "a," and "it" before analysis?
- A) To reduce dataset size only
- B) To improve grammatical accuracy of the source text
- C) To focus analysis on semantically meaningful words
- D) To improve audio transcription quality

**Q20. (Scenario)** A company operating in 12 countries wants every incoming support ticket automatically routed to the correctly localized analysis pipeline based on what language it's written in, before any sentiment or key phrase processing happens. Which Azure AI Language feature should run FIRST in this pipeline?
- A) Named entity recognition
- B) Key phrase extraction
- C) Language detection
- D) Sentiment analysis

---

## Section D — Document Intelligence (Q21–23)

**Q21. (Scenario)** A law firm receives thousands of scanned contracts in inconsistent formats and needs to extract party names, effective dates, and signature blocks into a structured database automatically. Which Azure AI capability is purpose-built for this?
- A) Azure AI Vision image classification
- B) Azure AI Document Intelligence (Content Understanding)
- C) Azure AI Language sentiment analysis
- D) Azure AI Speech-to-Text

**Q22.** What is required of a client application after submitting a document for ASYNCHRONOUS analysis in Azure AI Document Intelligence?
- A) Nothing further is needed; results return instantly
- B) The application must poll a status URL until the job completes
- C) The document must be deleted immediately
- D) The application must restart its Azure subscription

**Q23.** What is the main advantage of Document Intelligence's prebuilt models (e.g., invoice, receipt) over building a custom extraction solution from scratch?
- A) They require no Azure subscription at all
- B) They come pre-trained to recognize common document fields, reducing setup time and complexity
- C) They eliminate the need for any API calls
- D) They only work with handwritten documents

---

## Section E — Speech (Q24–26)

**Q24.** Why would a developer choose the Azure Speech SDK over only using a browser-based playground for a production voice application?
- A) The SDK allows speech recognition to be embedded directly into application code
- B) The SDK is the only way to upload audio files anywhere
- C) The SDK replaces the need for any Azure Speech resource
- D) The SDK is free while the playground is not

**Q25.** What does the Azure Text-to-Speech SDK handle on behalf of developers?
- A) Only voice selection, with audio file writing done manually
- B) Authentication, network communication, and audio generation
- C) Permanent storage of synthesized audio in Blob Storage automatically
- D) Manual transcription review

**Q26.** What role does a real-time Voice Live SDK play in a voice-enabled conversational agent?
- A) It stores audio recordings permanently
- B) It replaces the need for a microphone on the user's device
- C) It opens a real-time connection, streams audio, and handles spoken responses and interruptions
- D) It only works with pre-recorded audio files

---

## Section F — Generative AI & Agents (Q27–30)

**Q27. (Scenario)** A development team notices their generative AI assistant gives inconsistent answers to nearly identical questions. What should they try FIRST before assuming the infrastructure is at fault?
- A) Increase the underlying hardware capacity
- B) Refine the prompt's clarity and constraints
- C) Change the Azure subscription tier
- D) Disable logging to improve speed

**Q28.** Which component of a transformer-based LLM is responsible for examining the relationships between each token and the tokens around it?
- A) Positional encoding alone
- B) The attention mechanism
- C) The tokenizer's vocabulary file
- D) The billing meter

**Q29.** What best describes the function of Retrieval-Augmented Generation (RAG) in an enterprise generative AI solution?
- A) It increases the model's creative "temperature" setting
- B) It retrieves relevant content from an organization's own knowledge sources to ground model responses in real data
- C) It compresses the model to run faster
- D) It disables all content safety filters

**Q30. (Scenario)** A company publishes an agent in Microsoft Foundry rather than only using it inside the project's Playground. What is the primary benefit of publishing?
- A) It deletes the agent from the development environment
- B) It converts the agent into a managed Azure resource with a stable, shareable endpoint, without exposing the underlying project or source code
- C) It makes the agent free to run regardless of usage
- D) It restricts the agent to internal testing only

---

## ✅ Answer Key

| Q | Ans | Q | Ans | Q | Ans |
|---|-----|---|-----|---|-----|
| 1 | B | 11 | B | 21 | B |
| 2 | A | 12 | B | 22 | B |
| 3 | B | 13 | B | 23 | B |
| 4 | A, B | 14 | B | 24 | A |
| 5 | C | 15 | B | 25 | B |
| 6 | B | 16 | B | 26 | C |
| 7 | B | 17 | A, C | 27 | B |
| 8 | B | 18 | B | 28 | B |
| 9 | B | 19 | C | 29 | B |
| 10 | B | 20 | C | 30 | B |

---

## Answer Explanations

**Q1 — B (Transparency).** Transparency is about helping people understand how an AI system arrives at its outputs/decisions — directly relevant to an auditable, explainable government chatbot.

**Q2 — A.** Foundry is a unified platform for discovering, building, testing, evaluating, and deploying AI models and agents — not an identity service, image editor, or billing-only tool.

**Q3 — B.** A Foundry **resource** is the Azure-level container providing platform capabilities (compute, security, connections); a **project** is the workspace inside that resource where you actually build and organize your work.

**Q4 — A, B.** The model catalog/playgrounds and agent-building tools are genuine Foundry capability areas. Physical server racking, manual invoice printing, and spreadsheet macros are unrelated to a cloud AI platform.

**Q5 — C.** A unified, governed platform like Foundry meets the requirements of being secure, scalable, and manageable by a small non-technical team better than fragmented local models, manual tagging, or avoiding AI altogether.

**Q6 — B.** Keeping humans in the loop for high-stakes decisions supports accountability and helps catch/mitigate potential harms from model errors or bias — a core responsible AI practice.

**Q7 — B.** Evaluation and comparison tools let teams make informed model-selection decisions based on documented performance, not arbitrary choice.

**Q8 — B.** Computer vision works fundamentally with pixel data — the raw numeric values that make up an image — not file metadata or names.

**Q9 — B.** CNN filters extract numeric features (edges, textures, shapes) from raw pixel data, which the network then uses to learn patterns for classification.

**Q10 — B (Object detection).** Counting AND locating multiple objects within a frame (with bounding boxes) is the defining capability of object detection, beyond simple whole-image classification.

**Q11 — B.** A Vision Transformer applies the attention mechanism (borrowed from language transformers) to image patches, building contextual embeddings rather than just applying visual filters.

**Q12 — B.** Multimodal models can process and reason across more than one data type (e.g., text + images) simultaneously — a key feature of modern foundation models.

**Q13 — B.** Overnight, non-real-time, high-volume sentiment classification is exactly the use case for batch text analytics using Azure AI Language's sentiment analysis feature.

**Q14 — B (Stemming).** Stemming mechanically strips endings and can produce non-words (e.g., "glob" from "global"); lemmatization, by contrast, always returns a valid dictionary form.

**Q15 — B.** Distinguishing "Banks" (a name) from "banks" (institutions) preserves important semantic meaning that would otherwise be lost if both were normalized to the same token.

**Q16 — B (NER).** Named Entity Recognition specifically identifies and categorizes real-world entities (people, places, organizations) — distinct from key phrase extraction, which surfaces general important phrases without entity categorization.

**Q17 — A, C.** Semantic models understand context and word order (unlike bag-of-words statistical methods), and similar words cluster with similar vector orientations. They do NOT inherently require less training data, do NOT eliminate bias, and DO rely on numeric vector representations — so B, D, and E are false.

**Q18 — B.** Misreading sarcasm reflects a genuine limitation in the model's depth of language/context understanding, not a technical/infrastructure issue like tokenization, latency, or batching.

**Q19 — C.** Stop word removal's primary purpose is to let analysis focus on words that carry real semantic weight, improving the signal-to-noise ratio in text analysis — not about dataset size, grammar, or audio.

**Q20 — C (Language detection).** Before any sentiment or key phrase analysis can run correctly across multiple languages, the pipeline must first detect which language each ticket is written in to route it appropriately.

**Q21 — B.** Document Intelligence (Content Understanding) is purpose-built to extract structured fields like party names and dates from documents with inconsistent layouts — well beyond what basic OCR or sentiment analysis can do.

**Q22 — B.** Asynchronous analysis APIs require the client to poll a status endpoint until the job finishes, since results aren't returned synchronously in the initial request.

**Q23 — B.** Prebuilt models come pre-trained on common document types (invoices, receipts), dramatically reducing the setup and training effort compared to building a custom model from scratch.

**Q24 — A.** The SDK allows speech recognition capabilities to be built directly into an application's code for production use, rather than only being explorable in a browser-based testing playground.

**Q25 — B.** The Text-to-Speech SDK manages the underlying complexity — authentication, network calls, and audio generation — so developers don't have to implement these manually.

**Q26 — C.** A real-time Voice Live SDK manages live, bidirectional audio streaming — including handling interruptions — enabling natural spoken conversations with an agent.

**Q27 — B.** Inconsistent outputs for similar inputs are most often a prompt clarity/constraint issue first — refining the prompt is the standard first troubleshooting step before assuming infrastructure problems.

**Q28 — B (Attention mechanism).** The attention mechanism is specifically responsible for weighing how much influence each surrounding token has on the representation of the current token.

**Q29 — B.** RAG grounds model output by retrieving and injecting relevant content from an organization's actual data sources into the prompt context, reducing reliance on (and hallucination from) only the model's static training data.

**Q30 — B.** Publishing converts a Playground/development agent into a stable, governed, shareable Azure resource with its own endpoint — enabling integration into apps without exposing the underlying project.

---

## Domain Breakdown

| AI-900 Domain | Questions |
|---|---|
| Describe AI workloads and considerations (incl. Responsible AI, Foundry) | Q1–Q7 |
| Describe fundamental principles of computer vision | Q8–Q12 |
| Describe features of NLP workloads (Azure AI Language) | Q13–Q20 |
| Describe features of generative AI / document intelligence workloads | Q21–Q23, Q27–Q30 |
| Describe features of Speech workloads | Q24–Q26 |

---

## Scoring

- **27–30** → Excellent, exam-ready
- **21–26** → Good, review missed topics
- **Below 21** → Revisit weak domains before attempting the real exam

## Sources
Synthesized from: JDA Mock Test, JDA Mock Test 2, JDA Mock Test 3, NPower Assessments 1/3/4, "small once's after the model ends" notes, and Microsoft Learn AI-900 learning path modules.

*Track your attempts:*

| Date | Score | Notes |
|------|-------|-------|
|      | /30   |       |
