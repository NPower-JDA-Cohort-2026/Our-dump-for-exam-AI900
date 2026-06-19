---
tags: [jda, ai-900, mock-test, claude-generated]
source:
  - "All JDA Program notes, assessments, and Microsoft Learn AI-900 path"
created: 2026-06-18
questions: 30
goal: "Exam AI-900: Microsoft Azure AI Fundamentals"
---

# Mock Claude 1 — AI-900 Full Coverage Exam

**Instructions:** 30 questions covering the full AI-900 exam blueprint: AI workloads & responsible AI, Computer Vision, NLP & Azure AI Language, Document Intelligence, Speech, and Generative AI/Agents in Microsoft Foundry. Mix of multiple-choice, multiple-select, and scenario-based questions. Answer key and explanations are at the bottom — don't peek until you're done!

Related: [[JDA Mock Test]] · [[JDA Mock Test 2]] · [[JDA Mock Test 3]] · [[Mock Claude 2]]

---

## Section A — AI Workloads & Responsible AI (Q1–6)

**Q1.** A retailer wants a system that can look at photos of shelves and report which products are out of stock. Which type of AI workload is this primarily?
- A) Natural language processing
- B) Computer vision
- C) Knowledge mining
- D) Conversational AI

**Q2.** Which responsible AI principle is MOST directly addressed by ensuring an AI hiring tool performs equally well across all demographic groups?
- A) Transparency
- B) Fairness
- C) Accountability
- D) Privacy and security

**Q3.** A hospital deploys an AI triage assistant. Which responsible AI principle requires that clinicians remain able to override the AI's recommendations?
- A) Inclusiveness
- B) Reliability and safety
- C) Accountability
- D) Transparency

**Q4. (Multiple Select — choose 2)** Which of the following are examples of generative AI workloads? *(Select 2)*
- A) Classifying an email as spam or not spam
- B) Writing a draft blog post from a short outline
- C) Detecting faces in a security camera feed
- D) Generating a product image from a text description
- E) Calculating the average of a column in a spreadsheet

**Q5.** Which Azure resource type lets you provision and manage MULTIPLE different AI services (Vision, Language, Speech, etc.) under one single key and endpoint?
- A) A single-service resource
- B) An Azure AI multi-service (Azure AI services) resource
- C) A storage account
- D) A virtual network

**Q6.** A company wants to track AI project costs separately by department within the same Azure subscription. Which Azure construct should they use to organize and isolate resources?
- A) Resource groups
- B) Availability zones
- C) Virtual machines
- D) Content delivery networks

---

## Section B — Computer Vision (Q7–11)

**Q7.** Which computer vision capability draws a bounding box around each car in a parking lot photo and labels each one "car"?
- A) Image classification
- B) Object detection
- C) Optical character recognition
- D) Semantic segmentation

**Q8.** Which computer vision technique assigns a category label to an image as a whole, such as labeling a photo "beach" or "mountain"?
- A) Object detection
- B) Image classification
- C) Facial detection
- D) Spatial analysis

**Q9.** A security firm wants to count how many people enter a building through a specific doorway using video feeds, without identifying who they are. Which Azure AI Vision capability fits this need?
- A) Facial recognition
- B) Spatial analysis
- C) OCR
- D) Image generation

**Q10. (Multiple Select — choose 2)** Which of the following are valid use cases for Optical Character Recognition (OCR)? *(Select 2)*
- A) Extracting text from a scanned receipt
- B) Reading a license plate from a traffic camera image
- C) Detecting whether an image contains a dog or a cat
- D) Identifying the sentiment of a customer review
- E) Counting the number of objects in a warehouse photo

**Q11. (Scenario)** A logistics company photographs every package label before shipping and needs the shipping address and tracking number converted into searchable, structured text in their database. Which Azure AI capability should they implement?
- A) Azure AI Vision Image Analysis (tagging)
- B) Azure AI Vision OCR (Read API)
- C) Azure AI Language sentiment analysis
- D) Azure AI Speech transcription

---

## Section C — NLP & Azure AI Language (Q12–18)

**Q12.** What is the purpose of tokenization in natural language processing?
- A) To translate text into another language
- B) To break text down into smaller units for analysis
- C) To classify an image into a category
- D) To compress audio files

**Q13.** Which NLP technique determines how important a word is to one specific document relative to a larger collection of documents?
- A) Stemming
- B) TF-IDF (Term Frequency – Inverse Document Frequency)
- C) Lemmatization
- D) Stop word removal

**Q14.** Which Azure AI Language capability would you use to classify a batch of product reviews as positive, negative, or neutral?
- A) Key phrase extraction
- B) Sentiment analysis
- C) Named entity recognition
- D) Language detection

**Q15.** Why should language detection typically run BEFORE other text analysis tasks in an NLP pipeline?
- A) It compresses the text to save storage
- B) It selects the right language context needed for accurate downstream analysis
- C) It removes all punctuation automatically
- D) It replaces the need for tokenization

**Q16. (Multiple Select — choose 2)** Which of the following are purpose-built, deterministic Azure AI Language capabilities (as opposed to general-purpose generative AI text tasks)? *(Select 2)*
- A) PII (personally identifiable information) detection
- B) Free-form creative story generation
- C) Language detection
- D) Open-ended conversational chat
- E) Image captioning

**Q17. (Scenario)** A multinational bank wants to automatically scan customer complaint emails, detect and redact phone numbers, account numbers, and addresses before the emails are archived for compliance. Which Azure AI Language feature should they use?
- A) Key phrase extraction
- B) PII detection
- C) Sentiment analysis
- D) Entity linking

**Q18.** Vector embeddings in NLP are used to:
- A) Store raw audio waveforms
- B) Capture the semantic meaning and relationships between tokens in multi-dimensional space
- C) Compress images for faster loading
- D) Encrypt sensitive text data

---

## Section D — Document Intelligence & Information Extraction (Q19–22)

**Q19.** What is the key advantage of Azure AI Content Understanding (Document Intelligence) over basic OCR?
- A) It only works with handwritten text
- B) It understands document structure and maps extracted data to a defined schema
- C) It eliminates the need for any Azure subscription
- D) It is exclusively used for translating documents

**Q20.** In Azure AI Document Intelligence / Content Understanding, what is the role of an "analyzer"?
- A) It permanently stores extracted data in a database
- B) It defines how content should be processed and what structured fields are returned
- C) It converts JSON output into a PDF
- D) It generates new synthetic documents

**Q21.** When you submit content to an asynchronous document analysis API, what must your application typically do next?
- A) Nothing — results are always returned instantly in the same response
- B) Poll a status URL until the analysis job completes
- C) Restart the Azure subscription
- D) Re-upload the document in a different format

**Q22. (Scenario)** An accounts payable team receives hundreds of vendor invoices in different layouts every day and wants to automatically extract the vendor name, invoice date, line items, and total amount into a standard format for their ERP system. Which Azure AI capability is the best fit?
- A) Azure AI Vision image classification
- B) Azure AI Document Intelligence (prebuilt invoice model)
- C) Azure AI Language key phrase extraction
- D) Azure AI Speech-to-Text

---

## Section E — Speech (Q23–25)

**Q23.** Which Azure AI Speech capability converts spoken audio into written text?
- A) Speech synthesis
- B) Speech recognition (speech-to-text)
- C) Speaker recognition
- D) Translation

**Q24.** What does "prosody" refer to in speech synthesis (text-to-speech)?
- A) The volume level of the output audio file
- B) Natural pronunciation, rhythm, and cadence in generated speech
- C) The language detected from input text
- D) A method for compressing audio files

**Q25.** What is a phoneme?
- A) An AI model that generates audio
- B) The smallest unit of sound in speech
- C) A filter applied to remove background noise
- D) A unit used to measure audio file size

---

## Section F — Generative AI, LLMs & Agents in Foundry (Q26–30)

**Q26.** Fundamentally, large language models (LLMs) generate text by:
- A) Looking up exact matches in a fixed database
- B) Predicting the most probable next token based on patterns learned during training
- C) Running a fixed set of grammar rules
- D) Translating between hard-coded templates

**Q27.** What does "temperature" control when generating output from a generative AI model?
- A) The physical GPU temperature during training
- B) The randomness or creativity level of the model's output
- C) The size of the model's vocabulary
- D) The number of tokens billed per request

**Q28.** A model produces fluent, confident-sounding text that is factually incorrect and not grounded in any real source. What is this phenomenon called?
- A) Overfitting
- B) Hallucination
- C) Tokenization
- D) Quantization

**Q29.** What technique helps ground a generative AI model's responses in an organization's own private data rather than relying solely on its training data?
- A) Increasing the temperature setting
- B) Retrieval-augmented generation (RAG)
- C) Disabling content filters
- D) Reducing the context window

**Q30. (Scenario)** A company in Microsoft Foundry wants to package a model together with a system prompt and a set of callable tools (like a calculator and a knowledge search function) so it can autonomously complete multi-step customer support tasks. What are they building?
- A) A single REST API call
- B) An agent
- C) A storage account
- D) A virtual network

---

## ✅ Answer Key

| Q | Ans | Q | Ans | Q | Ans |
|---|-----|---|-----|---|-----|
| 1 | B | 11 | B | 21 | B |
| 2 | B | 12 | B | 22 | B |
| 3 | C | 13 | B | 23 | B |
| 4 | B, D | 14 | B | 24 | B |
| 5 | B | 15 | B | 25 | B |
| 6 | A | 16 | A, C | 26 | B |
| 7 | B | 17 | B | 27 | B |
| 8 | B | 18 | B | 28 | B |
| 9 | B | 19 | B | 29 | B |
| 10 | A, B | 20 | B | 30 | B |

---

## Answer Explanations

**Q1 — B (Computer vision).** Analyzing photos to identify product presence/absence is an image-based task, which falls under computer vision, not NLP, knowledge mining, or conversational AI.

**Q2 — B (Fairness).** Fairness is the principle that AI systems should treat all groups of people equitably and not produce biased or discriminatory outcomes.

**Q3 — C (Accountability).** Accountability means the people who design and deploy AI systems remain responsible for outcomes — keeping humans able to override decisions is a direct application of this.

**Q4 — B, D.** Writing a blog post and generating an image from text are both generative tasks (creating new content). Spam classification and face detection are discriminative/predictive tasks, and averaging a column is basic computation — none of these create new content.

**Q5 — B (Multi-service resource).** An Azure AI services multi-service resource provides one key/endpoint for access to multiple AI capabilities (Vision, Language, Speech, etc.), simplifying management versus provisioning each service separately.

**Q6 — A (Resource groups).** Resource groups are Azure's organizational containers used to group and manage related resources together, often for cost tracking and access control by team or department.

**Q7 — B (Object detection).** Object detection both identifies objects AND locates them with bounding boxes — distinct from image classification, which only labels the whole image.

**Q8 — B (Image classification).** Classification assigns one (or more) labels to an entire image without identifying specific object locations.

**Q9 — B (Spatial analysis).** Spatial analysis in Azure AI Vision analyzes movement and presence of people in video feeds (e.g., counting people crossing a line) without performing identity recognition.

**Q10 — A, B.** OCR extracts text from images — both a scanned receipt and a license plate photo are text-in-image scenarios. Detecting dog vs. cat is image classification; sentiment is an NLP task; counting objects is object detection — none involve reading text.

**Q11 — B (OCR / Read API).** Extracting address and tracking number text from a label photo into searchable structured text is the core function of OCR (Read API), not general image tagging.

**Q12 — B.** Tokenization breaks text into smaller units (tokens) as the foundational first step before any further analysis.

**Q13 — B (TF-IDF).** TF-IDF specifically measures term relevance to ONE document relative to its frequency across the whole corpus — this differentiates it from simple stemming or stop word removal, which don't compare across documents.

**Q14 — B (Sentiment analysis).** Classifying text as positive/negative/neutral is the definition of sentiment analysis.

**Q15 — B.** Running language detection first ensures the correct language-specific models and rules are applied to subsequent analysis steps (since NLP techniques are language-dependent).

**Q16 — A, C.** PII detection and language detection are purpose-built, deterministic Azure AI Language analyzers that return structured, repeatable output. Free-form story generation and open-ended chat are generative AI tasks (probabilistic, not deterministic); image captioning belongs to Vision, not Language.

**Q17 — B (PII detection).** PII detection identifies and can redact sensitive personal data like phone numbers, account numbers, and addresses — exactly the bank's compliance need.

**Q18 — B.** Embeddings are numeric vectors that encode semantic relationships — words with similar meaning have vectors pointing in similar directions in vector space.

**Q19 — B.** Document Intelligence/Content Understanding goes beyond raw text extraction (OCR) by understanding document structure and mapping fields to a predefined schema (e.g., "Invoice Total", "Vendor Name").

**Q20 — B.** An analyzer defines the processing logic and the structured output schema returned for a given document type.

**Q21 — B.** Asynchronous document analysis jobs require polling a status endpoint until processing completes, since results aren't available instantly within the initial request.

**Q22 — B.** Document Intelligence's prebuilt invoice model is specifically designed to extract structured fields (vendor, date, line items, totals) from varied invoice layouts — exactly this scenario.

**Q23 — B.** Speech recognition (speech-to-text) is the capability that converts spoken audio into written text.

**Q24 — B.** Prosody refers to the natural rhythm, stress, and intonation patterns that make synthesized speech sound human-like rather than robotic.

**Q25 — B.** A phoneme is the smallest distinguishable unit of sound in spoken language, the basic building block speech recognition and synthesis models work with.

**Q26 — B.** LLMs are fundamentally next-token prediction engines — generating text by repeatedly predicting the most probable next token given the preceding context.

**Q27 — B.** Temperature is a generation parameter that controls how random/creative vs. focused/deterministic the model's output is — higher temperature = more varied/creative output.

**Q28 — B (Hallucination).** Hallucination describes confident, fluent, but factually incorrect or fabricated output not grounded in real data.

**Q29 — B (RAG).** Retrieval-augmented generation retrieves relevant content from an organization's own knowledge sources and feeds it into the prompt, grounding the model's response in real, current data rather than relying purely on training data.

**Q30 — B (An agent).** An agent in Foundry combines a model, instructions (system prompt), and tools, enabling it to autonomously reason and act across multi-step tasks — exactly what's described.

---

## Domain Breakdown

| AI-900 Domain | Questions |
|---|---|
| Describe AI workloads and considerations (incl. Responsible AI) | Q1–Q6 |
| Describe fundamental principles of computer vision | Q7–Q11 |
| Describe features of NLP workloads (Azure AI Language) | Q12–Q18 |
| Describe features of generative AI / document intelligence workloads | Q19–Q22, Q26–Q30 |
| Describe features of Speech workloads | Q23–Q25 |

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
