---
tags: [jda, ai-900, mock-test, claude-generated, exam-style]
source:
  - "All JDA Program notes + real exam feedback from AI-900 passer (score 841)"
created: 2026-06-24
questions: 48
goal: "Exam AI-900: Microsoft Azure AI Fundamentals"
---

# Mock Claude 3 — AI-900 Exam Simulation (48 Questions) (thx to Smital)

> 💡 **Built from real exam feedback:** A classmate passed with 841/1000 and reported:
> - **48 questions total**
> - **Heavy on Computer Vision and Face Recognition** — many confusing ones
> - **Many yes/no (True/False) format questions**
> - Questions similar to those in Geetu's exam PDF

**Structure of this mock:**
- Part A: Computer Vision & Face API — 18 questions (heaviest section, mirrors real exam)
- Part B: Yes/No — True or False — 12 questions (mirrors real exam format)
- Part C: Document Intelligence, Speech & NLP — 10 questions
- Part D: Generative AI, ML Fundamentals & Responsible AI — 8 questions

Answer key and explanations at the bottom. No peeking!

Related: [[Mock Claude 1]] · [[Mock Claude 2]] · [[JDA Mock Test 3]]

---

## PART A — Computer Vision & Face Recognition (Q1–18)
*This section is the heaviest on the real exam. Read every option carefully — distractors are close.*

---

**Q1.** An application needs to locate human faces in a photo and draw a bounding box around each one, but does NOT need to identify whose face it is. Which capability should be used?
- A) Face recognition (face identification)
- B) Face detection
- C) Facial attribute analysis
- D) Image classification

---

**Q2.** Which Azure AI service is specifically designed to analyze and identify human faces in images?
- A) Azure AI Vision Image Analysis
- B) Azure AI Language
- C) Azure AI Face API
- D) Azure AI Custom Vision

---

**Q3.** A social media platform wants to automatically blur faces in user-uploaded photos before they are stored, to protect bystander privacy. Which Azure AI Vision capability supports this?
- A) Image classification
- B) Optical character recognition
- C) Face detection
- D) Object detection

---

**Q4.** What is the difference between **face detection** and **face recognition**?
- A) Face detection requires training on known individuals; face recognition does not
- B) Face detection locates faces in an image; face recognition identifies whose face it is by comparing against a known set
- C) They are the same capability with different names
- D) Face recognition only works on videos, not images

---

**Q5.** Which of the following is an example of **face recognition** (not just face detection)?
- A) Drawing a bounding box around a face in a crowd photo
- B) Counting how many faces are in an image
- C) Unlocking a phone by matching the user's face to a stored identity
- D) Blurring all faces in a photo

---

**Q6.** A building security system uses cameras to verify that an employee's face matches their registered identity before granting access. Which Azure AI capability is being used?
- A) Spatial analysis
- B) Face detection
- C) Face verification / recognition
- D) Image classification

---

**Q7.** Azure AI Face API can analyze facial attributes. Which of the following is an example of a facial attribute the API can return?
- A) The person's name and employee ID
- B) Estimated age, emotion, and whether the person is wearing glasses
- C) The person's home address derived from context
- D) The financial credit score of the detected person

---

**Q8.** Which computer vision task assigns a **single label** to an entire image (e.g., "this photo is of a beach")?
- A) Object detection
- B) Image classification
- C) Semantic segmentation
- D) Spatial analysis

---

**Q9.** Which computer vision task identifies **both the type and location** of multiple objects within a single image, drawing bounding boxes around each?
- A) Image classification
- B) Semantic segmentation
- C) Face detection
- D) Object detection

---

**Q10.** A retail analytics company wants to use overhead cameras to count how many customers are in each aisle at any given time, without identifying who they are. Which Azure AI Vision feature is most relevant?
- A) Face recognition
- B) Image classification
- C) Spatial analysis
- D) OCR

---

**Q11.** A convolutional neural network (CNN) uses **filters** during image processing. What is the primary purpose of these filters?
- A) To apply artistic color effects to images before display
- B) To compress image files to reduce storage costs
- C) To extract numeric features such as edges and shapes from raw pixel data
- D) To translate image captions into multiple languages

---

**Q12.** Which of the following best describes a **Vision Transformer (ViT)**?
- A) A model that applies sequential filters to image rows like a scanner
- B) A model that uses the attention mechanism to process image patches and create contextual embeddings
- C) A model exclusively designed to convert images into text transcriptions
- D) A tool that increases image resolution using upscaling algorithms

---

**Q13.** What does Azure AI Vision Image Analysis return when you submit an image?
- A) Only the pixel-by-pixel color values of the image
- B) SQL queries suitable for database storage of the image
- C) Tags, descriptions, categories, object locations, and confidence scores
- D) A compressed version of the image for storage

---

**Q14.** A manufacturing company trains a vision model to detect a **specific defect type** unique to their production line that no general-purpose model would recognize. Which Azure AI service should they use?
- A) Azure AI Vision (prebuilt Image Analysis)
- B) Azure AI Custom Vision (training on their own labeled images)
- C) Azure AI Face API
- D) Azure AI Document Intelligence

---

**Q15.** What does a **confidence score** represent when Azure AI Vision tags an image with "bicycle: 0.87"?
- A) The image contains exactly 0.87 bicycles
- B) The model is 87% confident that a bicycle is present in the image
- C) The image file size is 0.87 megabytes
- D) The bicycle occupies 87% of the image area

---

**Q16.** Computer vision models often produce poor results when the input images vary significantly in which of the following conditions?
- A) The number of text characters visible in the image
- B) The programming language used to call the API
- C) Lighting conditions and camera viewpoint angle
- D) The Azure subscription region selected

---

**Q17. (Scenario)** A photo-organization app wants to group vacation photos by scene type (beach, mountain, city) AND also show which specific objects (umbrella, tree, building) appear in each photo. Which combination of capabilities is needed?
- A) OCR + sentiment analysis
- B) Image classification + object detection
- C) Language detection + key phrase extraction
- D) Face detection + speech recognition

---

**Q18. (Scenario)** A security team reviews footage from 50 cameras. They need a system that can alert them when a **specific known individual** (on a watchlist) appears in any camera feed. Which capability is required?
- A) Face detection only
- B) Spatial analysis
- C) Face recognition (identification against a known person group)
- D) Image classification

---

## PART B — Yes / No — True or False (Q19–30)
*Answer Yes/True or No/False for each statement. This format appeared frequently on the real exam.*

---

**Q19.** Azure AI Face API can identify a specific person by name from a photo without any prior enrollment or training on that person's face.
- A) Yes — it identifies anyone automatically
- B) No — a person must first be enrolled in a Person Group before they can be identified

---

**Q20.** Azure AI Vision (the general-purpose Image Analysis service) and Azure AI Custom Vision are two different services — Custom Vision allows training on your own labeled images while Image Analysis uses prebuilt Microsoft models.
- A) Yes — this is correct
- B) No — they are the same service with different pricing tiers

---

**Q21.** Speech recognition and speech synthesis are the same Azure AI capability.
- A) Yes — both convert between text and audio
- B) No — speech recognition converts audio to text; speech synthesis converts text to audio

---

**Q22.** OCR (Optical Character Recognition) can extract text from a handwritten note photographed on a smartphone.
- A) Yes — modern OCR supports handwritten and printed text
- B) No — OCR only works on digitally typed text

---

**Q23.** A prebuilt Azure AI Document Intelligence invoice model can reliably extract fields from highly customized, non-standard invoice formats without any additional training.
- A) Yes — prebuilt models handle all invoice layouts automatically
- B) No — for non-standard layouts, a custom Document Intelligence model trained on labeled examples is recommended

---

**Q24.** Azure AI Language's PII detection can identify and redact personal information such as phone numbers and email addresses from text.
- A) Yes — this is a core capability of PII detection
- B) No — PII detection only highlights text, it cannot redact it

---

**Q25.** Increasing the **temperature** setting of a generative AI model makes its outputs more creative and varied (less deterministic).
- A) Yes — higher temperature = more randomness and creativity
- B) No — higher temperature makes the model more precise and conservative

---

**Q26.** An LLM that produces confident, fluent text containing made-up facts is said to be "overfitting."
- A) Yes — overfitting means the model memorizes and reproduces incorrect facts
- B) No — this phenomenon is called "hallucination," not overfitting

---

**Q27.** Azure AI Content Understanding can process audio files (not just documents and images) to extract structured information from recorded calls.
- A) Yes — Content Understanding supports audio, images, and documents
- B) No — it only processes images and PDFs

---

**Q28.** When using Azure AI Document Intelligence asynchronously, results are returned instantly in the same HTTP response as the submission request.
- A) Yes — the API is synchronous by design
- B) No — async jobs require polling a status URL until the job completes

---

**Q29.** Retrieval-Augmented Generation (RAG) helps reduce hallucinations in a generative AI model by grounding its responses in retrieved content from an organization's own data sources.
- A) Yes — RAG grounds responses in real retrieved data, reducing hallucination
- B) No — RAG only affects the model's token generation speed

---

**Q30.** Microsoft Foundry's model catalog is limited to Microsoft-only AI models and does not include open-source or third-party models.
- A) Yes — the catalog is exclusive to Microsoft models
- B) No — the catalog includes first-party, open-source, and third-party models from multiple providers

---

## PART C — Document Intelligence, Speech & NLP (Q31–40)

---

**Q31.** Your finance team receives scanned paper invoices daily. The first step before any field extraction should be:
- A) Running sentiment analysis on the invoice text
- B) Applying OCR to convert image text into machine-readable text
- C) Uploading directly to Azure AI Search
- D) Running language detection

---

**Q32.** What is the key distinction between **OCR** and **field extraction**?
- A) OCR is AI-powered; field extraction uses only rules
- B) OCR converts image text into readable characters; field extraction gives semantic meaning to those characters (e.g., "this is the invoice total")
- C) Field extraction works directly on raw images; OCR requires pre-processed files
- D) They perform identical functions with different names

---

**Q33.** A company processes invoices from 200 different vendors, each with completely different layouts. Which approach is most suitable for reliable field extraction?
- A) Template-based extraction with fixed coordinate rules per vendor
- B) Simple keyword search across raw OCR text
- C) AI-based layout-agnostic extraction using Azure AI Document Intelligence
- D) Manual data entry with human review for every document

---

**Q34.** A receipt-processing system extracts dates in inconsistent formats: "12/01/24", "Dec 1, 2024", and "01-12-2024". Downstream systems fail because of the inconsistency. Which pipeline step was skipped?
- A) OCR preprocessing
- B) Field detection
- C) Data normalization
- D) Image enhancement

---

**Q35.** Your team receives scanned photos of handwritten business cards and needs to populate a CRM with names, phone numbers, and emails automatically. Which Azure AI service is most suitable?
- A) Azure AI Vision Image Analysis
- B) Azure Content Understanding
- C) Azure AI Search
- D) Azure AI Document Intelligence

---

**Q36.** Which Azure AI Speech capability can distinguish between **multiple different speakers** in a single audio recording (e.g., a meeting with 5 participants)?
- A) Speech synthesis
- B) Batch transcription only
- C) Speaker recognition / diarization
- D) Language detection

---

**Q37.** A developer wants to build a voice assistant that converts spoken commands into text AND executes actions based on what was said. Which combination is needed?
- A) Bag-of-words + TF-IDF
- B) Speech-to-text + NLP intent classification
- C) OCR + entity recognition
- D) Speech synthesis + language detection

---

**Q38.** When configuring an Azure Speech Recognition model for a medical application where doctors use specialized terminology, what should you implement to improve accuracy?
- A) Increase the audio file's sample rate only
- B) Apply batch processing instead of real-time recognition
- C) Use a custom speech model or pronunciation dictionary with medical terms
- D) Switch from speech recognition to OCR

---

**Q39.** Which NLP feature would you use to **automatically identify and categorize** mentions of hospitals, medications, and doctors' names in clinical notes as named entities?
- A) Key phrase extraction
- B) Sentiment analysis
- C) Named Entity Recognition (NER)
- D) Language detection

---

**Q40. (Scenario)** A company with customers in 15 countries receives support tickets in many different languages. Before running any sentiment or key phrase analysis, what must happen first in the pipeline?
- A) PII detection to remove personal data
- B) Language detection to route each ticket to the correct localized model
- C) Named entity recognition to tag locations
- D) Text summarization to shorten the tickets

---

## PART D — Generative AI, ML Fundamentals & Responsible AI (Q41–48)

---

**Q41.** Which machine learning task is most appropriate for predicting whether a bank customer will default on a loan (yes or no)?
- A) Regression
- B) Clustering
- C) Binary classification
- D) Multiclass classification

---

**Q42.** A machine learning model trained to classify customer support tickets into 8 different categories (billing, returns, shipping, etc.) is performing which type of ML task?
- A) Binary classification
- B) Regression
- C) Reinforcement learning
- D) Multiclass classification

---

**Q43.** To evaluate how well a trained ML model generalizes to **new, unseen data**, which dataset should you use?
- A) The training dataset
- B) The validation dataset used during training
- C) The test dataset (held-out data not used in training)
- D) The full raw dataset before any split

---

**Q44.** An AI hiring tool consistently rates resumes from certain universities higher than others due to patterns in historical hiring data, even though those patterns reflect past bias. Which responsible AI principle is most at risk?
- A) Transparency
- B) Reliability and safety
- C) Fairness
- D) Inclusiveness

---

**Q45.** A government agency deploys an AI benefits eligibility system. Citizens complain they receive rejections with no explanation. Which responsible AI principle is being violated?
- A) Fairness
- B) Accountability
- C) Transparency
- D) Privacy and security

---

**Q46.** What does **Retrieval-Augmented Generation (RAG)** do in a Foundry-based enterprise AI solution?
- A) Increases the model's output temperature for more creative responses
- B) Retrieves relevant content from an organization's own knowledge base and injects it into the prompt to ground the model's response
- C) Compresses model weights to reduce deployment costs
- D) Disables content safety filters during inference

---

**Q47. (Scenario)** A company's generative AI assistant in Foundry keeps repeating factually wrong information even after the user corrects it in the same conversation. What should the development team improve?
- A) Increase the Azure compute tier
- B) Disable model versioning
- C) Improve the model's prompt context, system instructions, and grounding data (e.g., add RAG)
- D) Switch to a smaller language model

---

**Q48. (Scenario)** A Foundry team wants to make their agent available to other departments via a stable, shareable URL — without exposing the underlying Foundry project, source code, or development environment. What should they do?
- A) Share their Foundry project credentials with all departments
- B) Export the agent as a Python script and distribute it via email
- C) Publish the agent in Foundry, which creates a managed Azure resource with a dedicated endpoint
- D) Copy-paste the system prompt into each department's own Foundry project

---

---

## ✅ ANSWER KEY

### Part A — Computer Vision & Face Recognition

| Q | Ans | Q | Ans | Q | Ans |
|---|-----|---|-----|---|-----|
| 1 | B | 7 | B | 13 | C |
| 2 | C | 8 | B | 14 | B |
| 3 | C | 9 | D | 15 | B |
| 4 | B | 10 | C | 16 | C |
| 5 | C | 11 | C | 17 | B |
| 6 | C | 12 | B | 18 | C |

### Part B — Yes / No (True or False)

| Q | Ans |
|---|-----|
| 19 | B — No |
| 20 | A — Yes |
| 21 | B — No |
| 22 | A — Yes |
| 23 | B — No |
| 24 | A — Yes |
| 25 | A — Yes |
| 26 | B — No |
| 27 | A — Yes |
| 28 | B — No |
| 29 | A — Yes |
| 30 | B — No |

### Part C — Document Intelligence, Speech & NLP

| Q | Ans | Q | Ans |
|---|-----|---|-----|
| 31 | B | 36 | C |
| 32 | B | 37 | B |
| 33 | C | 38 | C |
| 34 | C | 39 | C |
| 35 | D | 40 | B |

### Part D — Generative AI, ML & Responsible AI

| Q | Ans |
|---|-----|
| 41 | C |
| 42 | D |
| 43 | C |
| 44 | C |
| 45 | C |
| 46 | B |
| 47 | C |
| 48 | C |

---

## ANSWER EXPLANATIONS

### Part A — Computer Vision & Face Recognition

**Q1 — B (Face detection).** Face detection locates faces and draws bounding boxes — it does NOT identify who those people are. Face recognition/identification is the additional step of matching a detected face to a known identity.

**Q2 — C (Azure AI Face API).** Face API is the dedicated service for face-related tasks: detection, verification, identification, and attribute analysis. Azure AI Vision handles general image analysis but is not face-specialized.

**Q3 — C (Face detection).** To blur faces, you must first locate them — that's face detection. You don't need to identify anyone, just find where the faces are so blurring can be applied.

**Q4 — B.** Detection = find and locate faces. Recognition = match a detected face against a known enrolled identity. This is a classic AI-900 exam distinction — expect it on the real exam.

**Q5 — C (Phone unlock by face match).** Unlocking by matching your face to a stored profile is face recognition (identification/verification). Options A, B, D all describe detection-level tasks — finding or counting faces without matching them to identities.

**Q6 — C (Face verification/recognition).** Comparing an employee's live face to their registered profile to grant access is face verification — a specific form of face recognition. Face detection alone would only find faces, not confirm identity.

**Q7 — B (Age, emotion, glasses).** Azure AI Face API returns facial attributes such as estimated age, detected emotion, head pose, smile, and accessories like glasses or masks. It does NOT return personal identity details like names or financial data.

**Q8 — B (Image classification).** Classification labels the whole image with one or more category tags — it doesn't locate individual objects within the image.

**Q9 — D (Object detection).** Object detection identifies what objects are present AND draws bounding boxes showing exactly where each one is — the key distinction from classification.

**Q10 — C (Spatial analysis).** Spatial analysis in Azure AI Vision is specifically designed to analyze people's movement and presence in physical spaces using video, without identifying individuals.

**Q11 — C (Extract numeric features).** CNN filters are mathematical operations that scan image regions to extract features like edges, textures, and shapes — this is how the network learns to recognize visual patterns. They are not decorative or compression tools.

**Q12 — B (Attention on image patches).** A ViT divides an image into patches, treats them like tokens (as in a language transformer), and uses the attention mechanism to build contextual relationships between patches — a fundamentally different approach than CNN filters.

**Q13 — C (Tags, descriptions, categories, confidence scores).** Azure AI Vision Image Analysis returns rich semantic output: object tags, image captions, category labels, detected objects with locations, and confidence scores for each prediction.

**Q14 — B (Azure AI Custom Vision).** When you need a model trained on YOUR specific labeled images to detect something a general model wouldn't know (like a proprietary defect type), Custom Vision is the right service.

**Q15 — B (87% confident a bicycle is present).** A confidence score is the model's probability estimate that its prediction is correct — 0.87 means 87% confidence, not a count or size.

**Q16 — C (Lighting and viewpoint).** Computer vision models trained on images from one perspective or lighting condition often struggle when those conditions change significantly — a well-known limitation covered directly in the NPower assessments.

**Q17 — B (Image classification + object detection).** Grouping by scene type (beach, mountain) = classification. Identifying specific objects within each photo (umbrella, tree) = object detection. Both are needed.

**Q18 — C (Face recognition / identification against a known person group).** To alert when a specific known person appears, you need face recognition — matching detected faces against a pre-enrolled group of known individuals. Detection alone just finds faces; it can't tell you whose they are.

---

### Part B — Yes / No Explanations

**Q19 — No.** Face identification requires the person to be enrolled in a **Person Group** first — the API needs reference images to compare against. It cannot identify strangers with no enrollment.

**Q20 — Yes.** Azure AI Vision (Image Analysis) uses Microsoft's prebuilt models for general analysis. Azure AI Custom Vision lets YOU train a model with your own labeled dataset. They are separate, distinct services.

**Q21 — No.** They are opposite directions: speech recognition = audio → text (input). Speech synthesis = text → audio (output). Confusing these two is a common exam trap.

**Q22 — Yes.** Azure AI Vision's OCR Read API supports both printed and handwritten text in photos taken with standard cameras or smartphones.

**Q23 — No.** Prebuilt models work well for common standard invoice formats. For unusual or non-standard layouts (e.g., merged cells, rotated fields, custom headers), you need to train a **custom** Document Intelligence model with your own labeled examples.

**Q24 — Yes.** PII detection is specifically built to identify and can redact (mask/remove) personal details like names, phone numbers, emails, and addresses from text for compliance purposes.

**Q25 — Yes.** Higher temperature = more randomness in token selection = more creative, varied output. Lower temperature = more deterministic and focused responses. This is exactly what temperature controls.

**Q26 — No.** Producing fluent but fabricated text is **hallucination** — a known LLM behavior where the model generates plausible-sounding but false content. Overfitting is a different ML problem where a model memorizes training data too closely and performs poorly on new data.

**Q27 — Yes.** Azure AI Content Understanding is multimodal — it processes audio files (transcribing and extracting structured fields from calls), images, PDFs, and other document types.

**Q28 — No.** Asynchronous Document Intelligence jobs require polling. The submission returns a job ID/status URL; you must check that URL repeatedly until the status changes to "succeeded" and then retrieve results.

**Q29 — Yes.** RAG retrieves relevant content from real knowledge sources (your documents, databases) and injects it into the model's context, giving it factual grounding and reducing the chance of hallucinated responses.

**Q30 — No.** The Foundry model catalog is an open hub including models from Microsoft (like GPT-4, Phi), open-source providers (Meta's Llama, Mistral), and other third-party vendors — not Microsoft-exclusive.

---

### Part C — Document Intelligence, Speech & NLP

**Q31 — B (OCR first).** Before any field extraction or analysis can happen on a scanned document, the image text must be converted to machine-readable characters via OCR. It's always the first step in a document processing pipeline.

**Q32 — B.** OCR reads characters from an image and produces raw text. Field extraction then interprets that raw text to understand what each piece means semantically — "this number is the invoice total, not the tax amount."

**Q33 — C (Document Intelligence / layout-agnostic extraction).** Template-based extraction breaks when layouts change. Keyword search is too fragile. Manual entry doesn't scale. AI-based layout-agnostic extraction (Document Intelligence) is designed for exactly this multi-vendor, multi-layout challenge.

**Q34 — C (Data normalization).** The pipeline extracted the date correctly but failed to standardize the format across all sources before passing it downstream. Data normalization — converting varied date formats into one consistent format — was the missing step.

**Q35 — D (Azure AI Document Intelligence).** Handwritten business cards are a form recognition task — extracting structured fields (name, phone, email) from a non-standard handwritten layout. Document Intelligence handles this better than general Image Analysis or AI Search.

**Q36 — C (Speaker recognition / diarization).** Speaker diarization identifies and separates different speakers in a shared audio recording — distinct from transcribing what was said (speech recognition).

**Q37 — B (Speech-to-text + NLP intent classification).** First convert spoken commands to text (STT), then classify the intent of that text using NLP to determine what action to take.

**Q38 — C (Custom speech model / pronunciation dictionary).** Medical terminology (drug names, procedures, anatomical terms) is not well covered by standard speech models. Custom speech models and pronunciation dictionaries trained on domain-specific vocabulary significantly improve accuracy.

**Q39 — C (Named Entity Recognition).** NER specifically identifies and categorizes real-world entities in text — people, organizations, locations, medical terms — exactly what's needed for clinical note analysis.

**Q40 — B (Language detection first).** You cannot run accurate sentiment analysis or key phrase extraction without knowing the language first. Language detection routes each ticket to the correct language-specific processing pipeline before any deeper analysis.

---

### Part D — Generative AI, ML & Responsible AI

**Q41 — C (Binary classification).** Predicting one of exactly two outcomes (default / no default, yes / no, fraud / not fraud) is binary classification. Regression predicts continuous numeric values; clustering groups unlabeled data; multiclass handles 3+ categories.

**Q42 — D (Multiclass classification).** Classifying into 8 distinct categories is multiclass classification (more than 2 classes, one per ticket).

**Q43 — C (Test dataset).** The test dataset is held out entirely during training and validation — it's the gold standard for evaluating true generalization to unseen data. Using training or validation data would give artificially optimistic results.

**Q44 — C (Fairness).** When a model systematically favors or disadvantages a group due to bias in training data, this is a fairness violation — one of the core responsible AI principles.

**Q45 — C (Transparency).** Transparency requires that AI systems communicate how they work and why they make decisions. Unexplained rejections with no reasoning given is a transparency failure — people can't understand or contest the decision.

**Q46 — B (RAG retrieves and grounds responses).** RAG pulls relevant content from an organization's own knowledge sources and adds it to the prompt context, so the model answers from real, current data rather than relying solely on what it learned during pre-training.

**Q47 — C (Improve prompt context, system instructions, and grounding data).** A model repeating wrong information despite user corrections is a grounding/context problem. Better system instructions, clearer prompt design, and RAG to provide factual grounding are the right solutions — not hardware upgrades.

**Q48 — C (Publish the agent in Foundry).** Publishing creates a managed Azure resource with a stable, shareable REST endpoint. Other departments can call it without ever seeing the Foundry project, source code, or system prompt — exactly designed for this use case.

---

## Domain Breakdown

| Domain | Questions | Weight in this mock |
|---|---|---|
| Computer Vision (general) | Q1, Q8–Q17 | Heavy |
| Face Detection & Recognition | Q1–Q7, Q18–Q20 | **Heaviest — mirrors real exam** |
| Yes/No / True-False format | Q19–Q30 | **Mirrors real exam format** |
| Document Intelligence & OCR | Q31–Q35 | Medium |
| Speech | Q36–Q38 | Medium |
| NLP & Azure AI Language | Q39–Q40 | Light |
| Generative AI & Agents | Q46–Q48 | Light |
| ML Fundamentals | Q41–Q43 | Light |
| Responsible AI | Q44–Q45 | Light |

---

## 🎯 Top Traps on the Real Exam (based on 841-score feedback)

⚠️ **Trap 1: Face Detection vs. Face Recognition**
Detection = locate faces. Recognition = identify WHO they are. Many confusing questions swap these.

⚠️ **Trap 2: Custom Vision vs. Azure AI Vision**
Prebuilt Vision = general-purpose, no training needed. Custom Vision = you label your own images and train a custom model. Know when each applies.

⚠️ **Trap 3: Yes/No format hides known traps**
"Can Face API identify someone without enrollment?" → No. "Does async Document Intelligence return results instantly?" → No. These look easy but are written to catch you.

⚠️ **Trap 4: Binary vs. Multiclass classification**
Yes/no outcomes = binary. 3+ category outcomes = multiclass. The exam uses scenario phrasing that makes you second-guess yourself.

⚠️ **Trap 5: Hallucination vs. Overfitting**
Fluent but wrong text = hallucination. Memorizing training data = overfitting. Both are mentioned in questions — don't swap them.

---

## Scoring

- **44–48** → Excellent, exam-ready (above 841 target)
- **36–43** → Good — review Part A (Computer Vision/Face) closely
- **Below 36** → Focus on Computer Vision, Face API, and Yes/No traps before sitting the exam

*Track your attempts:*

| Date | Score | Weakest Section | Notes |
|------|-------|-----------------|-------|
|      | /48   |                 |       |
