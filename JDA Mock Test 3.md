# JDA Mock Test 3 — AI-900: Azure AI Language & NLP
**Based on:** Microsoft Learn Modules
- Get started with text analysis in Azure (Foundry)
- Introduction to natural language processing concepts

**Total Questions:** 30 | **Time Suggested:** 60 minutes
**Question Types:** 20 Multiple Choice · 5 Multiple Select · 5 Scenario-Based

> ⚠️ **Answer Explanations are in a separate section at the bottom of this file.**

---

## EXAM QUESTIONS

---

### Question 1
**Type:** Multiple Choice | **Difficulty:** Easy

What is the primary purpose of **tokenization** in natural language processing?

- A. Translating text from one language to another
- B. Breaking down text into smaller units for processing and analysis
- C. Identifying the sentiment of a document
- D. Removing all punctuation and numbers from text

---

### Question 2
**Type:** Multiple Choice | **Difficulty:** Easy

Which Azure service provides **purpose-built, deterministic analyzers** for specific NLP tasks such as language detection and PII detection?

- A. Azure Machine Learning
- B. Azure Cognitive Search
- C. Azure Language in Foundry tools
- D. Azure Bot Service

---

### Question 3
**Type:** Multiple Choice | **Difficulty:** Easy

What does **sentiment analysis** classify text as?

- A. Entities, locations, and dates
- B. Languages and dialects
- C. Positive, negative, or neutral
- D. Key phrases and topics

---

### Question 4
**Type:** Multiple Choice | **Difficulty:** Easy

In the context of NLP, what are **stop words**?

- A. Words that always appear at the end of a sentence
- B. Words with the highest TF-IDF score in a document
- C. Common words like "the", "a", or "it" that add little semantic meaning and are often excluded from analysis
- D. Words that trigger sentiment classification

---

### Question 5
**Type:** Multiple Choice | **Difficulty:** Easy

What does **language detection** return alongside the identified language?

- A. A list of key phrases
- B. A confidence score
- C. A sentiment label
- D. A list of named entities

---

### Question 6
**Type:** Multiple Choice | **Difficulty:** Easy

Which NLP pre-processing technique consolidates words by stripping word endings such as "ing", "ed", and "s" so they share the same root token?

- A. Lemmatization
- B. Stop word removal
- C. Stemming
- D. Parts of speech tagging

---

### Question 7
**Type:** Multiple Choice | **Difficulty:** Easy

What is **key phrase extraction** used for?

- A. Detecting the language a document is written in
- B. Identifying the main concepts and topics from unstructured text
- C. Redacting personally identifiable information from documents
- D. Translating text between languages

---

### Question 8
**Type:** Multiple Choice | **Difficulty:** Medium

A developer wants **consistent, structured, and deterministic** output for a text analysis pipeline that processes thousands of customer support tickets per day. Which approach best meets this requirement?

- A. Use a general-purpose AI model in the Foundry portal chat playground
- B. Use Azure Language in Foundry tools with purpose-built analyzers
- C. Use Azure Bot Service with LUIS
- D. Use Azure Cognitive Search with semantic ranking

---

### Question 9
**Type:** Multiple Choice | **Difficulty:** Medium

What is the key difference between **stemming** and **lemmatization**?

- A. Stemming uses statistical models; lemmatization uses neural networks
- B. Stemming simply removes word endings; lemmatization uses linguistic rules to produce a valid dictionary word
- C. Stemming only works on verbs; lemmatization works on all parts of speech
- D. Stemming increases vocabulary size; lemmatization reduces it

---

### Question 10
**Type:** Multiple Choice | **Difficulty:** Medium

A document contains the text: *"On May 2nd, 2017, John Smith visited New York."* Which Azure Language capability would identify **John Smith** as a Person and **New York** as a Location?

- A. Sentiment analysis
- B. Key phrase extraction
- C. Named entity recognition
- D. Language detection

---

### Question 11
**Type:** Multiple Choice | **Difficulty:** Medium

What does **TF-IDF** stand for, and what problem does it solve?

- A. Text Frequency – Inverse Data Filter; it removes duplicate documents
- B. Term Frequency – Inverse Document Frequency; it identifies which terms are most relevant to a specific document compared to a larger corpus
- C. Token Frequency – Internal Document Format; it formats tokens for machine learning models
- D. Term Frequency – Indexed Document File; it stores indexed tokens for fast retrieval

---

### Question 12
**Type:** Multiple Choice | **Difficulty:** Medium

In TF-IDF analysis across two documents, if the word **"Microsoft"** appears in both documents, what will its IDF value be (assuming only 2 documents in the corpus)?

- A. 2.0
- B. 1.0
- C. 0.5
- D. 0 (zero)

---

### Question 13
**Type:** Multiple Choice | **Difficulty:** Medium

Which text analysis technique uses a **graph-based algorithm** to score sentences by their similarity to other sentences in a document, and is commonly used for extractive summarization?

- A. Bag-of-words
- B. TF-IDF
- C. TextRank
- D. Named entity recognition

---

### Question 14
**Type:** Multiple Choice | **Difficulty:** Medium

What is **PII detection** in Azure Language primarily used for?

- A. Classifying documents into positive or negative sentiment
- B. Identifying and optionally redacting personal details such as names, phone numbers, and addresses from text
- C. Detecting the primary language of a document
- D. Extracting key business terms from contracts

---

### Question 15
**Type:** Multiple Choice | **Difficulty:** Medium

Which of the following best describes **word embeddings** in semantic language models?

- A. A lookup table mapping each word to an integer ID
- B. Multi-dimensional numerical vectors that encode the semantic meaning and relationships of words
- C. A list of stop words filtered out before model training
- D. A frequency count of how many times each word appears in a corpus

---

### Question 16
**Type:** Multiple Choice | **Difficulty:** Medium

What is the difference between **extractive** and **abstractive** summarization?

- A. Extractive creates new text; abstractive selects original sentences
- B. Extractive selects sentences from the original text; abstractive generates new language that captures key themes
- C. Extractive uses neural networks; abstractive uses TF-IDF
- D. There is no difference; both produce identical outputs

---

### Question 17
**Type:** Multiple Choice | **Difficulty:** Challenging

A data scientist calculates **cosine similarity** between two word vectors and gets a value of **0.99**. What does this indicate?

- A. The two words are completely unrelated
- B. The two words are semantically very similar
- C. One word is the antonym of the other
- D. The vectors are pointing in opposite directions

---

### Question 18
**Type:** Multiple Choice | **Difficulty:** Challenging

Using vector arithmetic: if **dog** = [0.8, 0.6, 0.1] and **young** = [0.1, 0.1, 0.3], what semantic concept does **dog + young** produce?

- A. Cat
- B. Kitten
- C. Puppy
- D. Ball

---

### Question 19
**Type:** Multiple Choice | **Difficulty:** Challenging

Which NLP technique assigns each token a grammatical label such as **noun**, **verb**, or **adjective** based on its role and context in a sentence?

- A. N-gram extraction
- B. Text normalization
- C. Parts of speech (POS) tagging
- D. Stemming

---

### Question 20
**Type:** Multiple Choice | **Difficulty:** Challenging

A general-purpose AI model in Microsoft Foundry is asked to perform sentiment analysis. A developer then asks for a sentence-by-sentence breakdown in the same conversation. Which capability makes this possible?

- A. The model applies TF-IDF to re-score sentences
- B. The model maintains context and responds to natural language follow-up prompts
- C. The model uses Azure Language's PII detection to filter the sentences
- D. The model re-tokenizes the input using stemming before each follow-up

---

### Question 21
**Type:** Multiple Select | **Difficulty:** Easy
*(Select ALL answers that apply)*

Which of the following tasks can a **general-purpose AI model** in Microsoft Foundry perform WITHOUT additional training or configuration? *(Select all that apply)*

- A. Key phrase extraction
- B. Sentiment analysis
- C. Text translation
- D. Training a custom NER model
- E. Document summarization

---

### Question 22
**Type:** Multiple Select | **Difficulty:** Medium
*(Select ALL answers that apply)*

Which of the following are valid **NLP pre-processing techniques** that can be applied during tokenization? *(Select all that apply)*

- A. Stop word removal
- B. Stemming
- C. Cosine similarity calculation
- D. N-gram extraction
- E. Parts of speech (POS) tagging

---

### Question 23
**Type:** Multiple Select | **Difficulty:** Medium
*(Select ALL answers that apply)*

A developer is using **Azure Language in Foundry tools**. Which of the following capabilities are available as purpose-built analyzers? *(Select all that apply)*

- A. Language detection
- B. PII detection
- C. Custom vision model training
- D. Sentiment analysis (via general-purpose model)
- E. Named entity recognition

---

### Question 24
**Type:** Multiple Select | **Difficulty:** Challenging
*(Select ALL answers that apply)*

Which of the following correctly describe **TF-IDF**? *(Select all that apply)*

- A. A word that appears in every document in a corpus will have an IDF of 0
- B. TF-IDF is best used for analyzing a single document in isolation
- C. A high TF-IDF score means a word is frequent in one document but rare across others
- D. TF-IDF helps differentiate documents that share common themes
- E. Frequency analysis alone is sufficient to achieve the same result as TF-IDF

---

### Question 25
**Type:** Multiple Select | **Difficulty:** Challenging
*(Select ALL answers that apply)*

Which of the following are TRUE about **semantic vector embeddings**? *(Select all that apply)*

- A. Semantically similar words tend to have vectors pointing in similar directions
- B. Cosine similarity can be used to measure how related two word vectors are
- C. Vector arithmetic such as addition and subtraction can reveal linguistic relationships between words
- D. Embeddings ignore the context in which a word appears
- E. The attention mechanism in modern models produces contextualized embeddings

---

### Question 26
**Type:** Scenario-Based | **Difficulty:** Medium

**Scenario:** Contoso Bank receives thousands of customer complaint emails daily. The compliance team needs to automatically scan these emails and **remove customer names, phone numbers, and account-related addresses** before storing them in a database, to comply with privacy regulations.

Which Azure Language capability should they use?

- A. Key phrase extraction
- B. Sentiment analysis
- C. PII detection
- D. Language detection

---

### Question 27
**Type:** Scenario-Based | **Difficulty:** Medium

**Scenario:** Adventure Works runs a multilingual e-commerce platform serving customers in Canada, France, and Japan. Before routing customer reviews to the appropriate regional analysis pipeline, the system needs to **automatically identify which language each review is written in**.

Which Azure Language feature should be implemented first?

- A. Named entity recognition
- B. Key phrase extraction
- C. Sentiment analysis
- D. Language detection

---

### Question 28
**Type:** Scenario-Based | **Difficulty:** Medium

**Scenario:** A research team has a corpus of 500 scientific articles about cloud computing. They want to find **which specific terms are most uniquely important to each individual article** compared to the broader collection. Simple word frequency counts are returning the same common terms ("cloud", "Azure", "data") across all articles, making differentiation impossible.

Which technique should the team apply?

- A. Stop word removal only
- B. TextRank summarization
- C. TF-IDF (Term Frequency – Inverse Document Frequency)
- D. Cosine similarity between article pairs

---

### Question 29
**Type:** Scenario-Based | **Difficulty:** Challenging

**Scenario:** Fabrikam is building a customer feedback analysis system. They need output that is **predictable, structured, and suitable for automated downstream processing** — for example, always returning a JSON object with defined fields. A colleague suggests using a general-purpose AI model in the Foundry chat playground for this purpose.

Is this the right approach? What should Fabrikam use instead, and why?

- A. Yes — general-purpose models always return structured JSON by default
- B. No — they should use Azure Language in Foundry tools, which provides deterministic, structured output well-suited for automated pipelines
- C. No — they should use Azure Bot Service, which is designed for structured data extraction
- D. Yes — the Foundry chat playground supports JSON output mode for all tasks

---

### Question 30
**Type:** Scenario-Based | **Difficulty:** Challenging

**Scenario:** A data science team is building a text summarization tool. For a given article about cloud computing, they model each sentence as a node and create weighted connections between sentences based on word overlap. Sentences that connect strongly to many other important sentences receive higher scores, and the top-scored sentences are selected as the summary.

Which algorithm are they implementing?

- A. Bag-of-words with Naive Bayes classification
- B. TF-IDF with frequency thresholding
- C. TextRank extractive summarization
- D. Cosine similarity document clustering

---

---

## ANSWER KEY

| Q | Answer | Q | Answer |
|---|--------|---|--------|
| 1 | B | 16 | B |
| 2 | C | 17 | B |
| 3 | C | 18 | C |
| 4 | C | 19 | C |
| 5 | B | 20 | B |
| 6 | C | 21 | A, B, C, E |
| 7 | B | 22 | A, B, D, E |
| 8 | B | 23 | A, B, E |
| 9 | B | 24 | A, C, D |
| 10 | C | 25 | A, B, C, E |
| 11 | B | 26 | C |
| 12 | D | 27 | D |
| 13 | C | 28 | C |
| 14 | B | 29 | B |
| 15 | B | 30 | C |

---

---

## ANSWER EXPLANATIONS

---

### Q1 — Tokenization (Easy)
**Correct: B**
Tokenization is the foundational first step in NLP — it breaks a text corpus into individual tokens (words, subwords, or punctuation) so they can be counted, analyzed, and fed into models.
- A: Translation is a separate NLP task, not tokenization.
- C: Sentiment is a downstream task that comes after tokenization.
- D: Punctuation removal is *text normalization*, a pre-processing step that may happen before or during tokenization, not tokenization itself.

---

### Q2 — Azure Language Service (Easy)
**Correct: C**
Azure Language in Foundry tools provides purpose-built, specialized analyzers (language detection, PII detection, etc.) that return deterministic, structured output — unlike general-purpose AI models.
- A: Azure Machine Learning is a platform for building and training custom ML models, not a text analysis service.
- B: Azure Cognitive Search is a search platform; it can use AI enrichment but is not a text analysis service.
- D: Azure Bot Service is for building chatbots and conversational agents.

---

### Q3 — Sentiment Analysis (Easy)
**Correct: C**
Sentiment analysis classifies text emotional tone as positive, negative, or neutral. It can also provide sentence-level breakdowns.
- A: Entity extraction, not sentiment.
- B: Language detection, not sentiment.
- D: Key phrase extraction, not sentiment.

---

### Q4 — Stop Words (Easy)
**Correct: C**
Stop words are common functional words (the, a, it, is) that appear frequently but carry little semantic content. Removing them helps NLP models focus on meaningful terms.
- A: Stop words are not defined by their position in a sentence.
- B: Words with high TF-IDF scores are the *opposite* of stop words — they are highly distinctive.
- D: Stop words don't trigger sentiment; they are removed to improve analysis quality.

---

### Q5 — Language Detection Output (Easy)
**Correct: B**
Azure Language's language detection returns the detected language name, its ISO 6391 code, AND a confidence score (e.g., Spanish, "es", 1.00).
- A: Key phrase extraction is a separate feature.
- C: Sentiment labels come from sentiment analysis.
- D: Named entity lists come from NER, not language detection.

---

### Q6 — Stemming (Easy)
**Correct: C**
Stemming strips word endings ("ing", "ed", "s") to reduce words to their root form — e.g., "powering", "powered", "powerful" → "power". It's a fast, rule-based approach.
- A: Lemmatization also reduces words to a base form but uses linguistic rules to ensure the result is a valid dictionary word — it's more sophisticated than stemming.
- B: Stop word removal eliminates common words, not word endings.
- D: POS tagging labels words by grammatical category, not reduces them.

---

### Q7 — Key Phrase Extraction (Easy)
**Correct: B**
Key phrase extraction identifies the main concepts, topics, and important phrases from unstructured text — useful for search indexing, document tagging, and summarization.
- A: That's language detection.
- C: That's PII detection.
- D: That's machine translation.

---

### Q8 — Service Selection: Deterministic Output (Medium)
**Correct: B**
Azure Language in Foundry tools uses statistical, purpose-built analyzers that produce structured, deterministic output — the same input will always produce the same result. This is critical for automated pipelines.
- A: General-purpose AI models are probabilistic and conversational — they produce variable output depending on prompt phrasing, making them less suitable for automated pipelines requiring consistent structure.
- C: LUIS (Language Understanding) is deprecated and part of older Azure architecture.
- D: Cognitive Search with semantic ranking is a search retrieval feature, not a text analysis pipeline tool.

---

### Q9 — Stemming vs Lemmatization (Medium)
**Correct: B**
Stemming mechanically chops off word endings (which can produce non-words like "run" from "running" but also "glob" from "global"). Lemmatization applies vocabulary and grammar rules to always return a valid word (e.g., "running" → "run", "global" → "globe").
- A: Both can use statistical models; the distinction is about how the root is derived, not the model type.
- C: Both techniques apply to all word types, not just verbs.
- D: Both reduce vocabulary size by grouping word variants — this is their shared purpose.

---

### Q10 — Named Entity Recognition (Medium)
**Correct: C**
Named Entity Recognition (NER) identifies and categorizes real-world entities in text — people (John Smith), locations (New York), organizations, dates, quantities, etc.
- A: Sentiment analysis evaluates emotional tone.
- B: Key phrase extraction identifies important phrases but does not categorize them as Person, Location, etc.
- D: Language detection identifies what language text is written in.

---

### Q11 — TF-IDF Definition (Medium)
**Correct: B**
TF-IDF (Term Frequency – Inverse Document Frequency) calculates a relevance score for each term in a document relative to an entire corpus. High TF-IDF = the word appears often in THIS document but rarely in OTHERS — meaning it's distinctive to that document.
- A, C, D: All fabricated definitions with no basis in the module content.

---

### Q12 — TF-IDF IDF Value for Universal Terms (Medium)
**Correct: D — 0 (zero)**
IDF is calculated as log(N / df(t)). If "Microsoft" appears in both documents (N=2, df=2), then IDF = log(2/2) = log(1) = 0. This means the word carries NO discriminative weight — it's too common across the corpus.
- A, B, C: These values would require the word to appear in fewer documents than the total.

---

### Q13 — TextRank (Medium)
**Correct: C**
TextRank is a graph-based, unsupervised algorithm that models sentences as nodes and connects them with edges weighted by similarity. The highest-ranked sentences (those most similar to many other important sentences) are extracted as a summary.
- A: Bag-of-words is a feature extraction method, not a summarization algorithm.
- B: TF-IDF identifies relevant terms across documents, not summaries within a document.
- D: NER identifies entities — it doesn't generate summaries.

---

### Q14 — PII Detection (Medium)
**Correct: B**
PII (Personally Identifiable Information) detection identifies and can redact sensitive personal details — names, phone numbers, email addresses, physical addresses — to help organizations comply with privacy regulations (e.g., GDPR, HIPAA).
- A: That's sentiment analysis.
- C: That's language detection.
- D: Key phrase extraction identifies business terms but does not flag or redact personal data.

---

### Q15 — Word Embeddings (Medium)
**Correct: B**
Word embeddings are dense, multi-dimensional numerical vectors (arrays of numbers) that encode the semantic meaning of words. Words with similar meanings have vectors pointing in similar directions.
- A: A lookup table mapping words to integers is a simple vocabulary index, not an embedding.
- C: Stop word lists are a pre-processing tool, not an embedding.
- D: Frequency counts are the basis of bag-of-words, not semantic embeddings.

---

### Q16 — Extractive vs Abstractive Summarization (Medium)
**Correct: B**
Extractive summarization selects the most important sentences directly from the original text (no new words are generated). Abstractive summarization generates new language that captures the key themes — more like how a human would write a summary.
- A: This is the reverse of the correct definitions.
- C: The techniques used don't neatly split this way — TextRank enables extractive; modern LLMs enable abstractive.
- D: They produce distinctly different outputs.

---

### Q17 — Cosine Similarity Interpretation (Challenging)
**Correct: B**
Cosine similarity ranges from -1 to 1. A value of 0.99 is very close to 1, indicating the two vectors point in nearly the same direction — meaning the words are semantically very similar (e.g., "dog" and "puppy").
- A: Unrelated words would have cosine similarity near 0.
- C: Antonyms might have low (near 0) or sometimes high similarity depending on context — but the value itself doesn't directly indicate antonym status.
- D: Vectors pointing in opposite directions would produce a cosine similarity near -1.

---

### Q18 — Vector Arithmetic (Challenging)
**Correct: C — Puppy**
dog [0.8, 0.6, 0.1] + young [0.1, 0.1, 0.3] = [0.9, 0.7, 0.4], which matches the vector for "puppy". The "young" vector encodes the semantic transformation from an adult animal to its juvenile counterpart.
- A: Cat's vector is [0.7, 0.5, 0.2] — that's not the result here.
- B: Kitten = cat + young = [0.8, 0.6, 0.5].
- D: Ball has a distinctly different vector [0.3, 0.9, 0.1].

---

### Q19 — POS Tagging (Challenging)
**Correct: C**
Parts of speech (POS) tagging assigns grammatical labels (noun, verb, adjective, adverb, etc.) to each token using both the token itself and its surrounding context.
- A: N-gram extraction identifies multi-word phrases (bigrams, trigrams), not grammatical labels.
- B: Text normalization standardizes text (lowercase, punctuation removal) — it doesn't label grammar.
- D: Stemming strips word endings — it doesn't identify grammatical roles.

---

### Q20 — General-Purpose AI Context Awareness (Challenging)
**Correct: B**
General-purpose AI models maintain conversation context. Because they understand natural language prompts, a user can ask a follow-up question in the same conversation to refine the output — e.g., asking for sentence-by-sentence breakdown after an initial sentiment request.
- A: TF-IDF is not used to re-score sentences during a conversation.
- C: PII detection is a separate Azure Language feature and is not applied inside sentiment conversations.
- D: Re-tokenization doesn't happen between follow-up messages in a chat playground.

---

### Q21 — General-Purpose AI Capabilities (Easy) [Multiple Select]
**Correct: A, B, C, E**
General-purpose AI models handle key phrase extraction, sentiment analysis, text translation, and document summarization through natural language prompts — no training required.
- D (Incorrect): Training a custom NER model is a machine learning task that requires labeled data and a training pipeline — this is not something a general-purpose AI model does "out of the box" in the playground.

---

### Q22 — NLP Pre-processing Techniques (Medium) [Multiple Select]
**Correct: A, B, D, E**
Stop word removal, stemming, N-gram extraction, and POS tagging are all standard NLP pre-processing techniques applied during or after tokenization.
- C (Incorrect): Cosine similarity is a mathematical calculation used to compare word vectors AFTER tokens have been converted into embeddings — it is not a tokenization pre-processing step.

---

### Q23 — Azure Language Capabilities (Medium) [Multiple Select]
**Correct: A, B, E**
Azure Language in Foundry tools provides purpose-built deterministic analyzers for: language detection, PII detection, and named entity recognition.
- C (Incorrect): Custom vision model training is part of Azure AI Vision, not Azure Language.
- D (Incorrect): Sentiment analysis in this context is performed via the general-purpose AI model, not as a purpose-built Azure Language analyzer (based on module content). The module distinguishes these two approaches separately.

---

### Q24 — TF-IDF Facts (Challenging) [Multiple Select]
**Correct: A, C, D**
- A: If a word appears in all N documents, IDF = log(N/N) = log(1) = 0 — confirmed in the module.
- C: High TF-IDF means frequent in one document, rare in others — this is the core definition.
- D: TF-IDF helps discriminate between documents sharing common terms.
- B (Incorrect): TF-IDF's value is in comparing across a corpus — simple frequency is sufficient for a single document.
- E (Incorrect): Frequency analysis cannot distinguish documents that share the same top terms — TF-IDF was designed to solve exactly this problem.

---

### Q25 — Semantic Vector Embeddings (Challenging) [Multiple Select]
**Correct: A, B, C, E**
- A: Similar words have similar vector orientations — confirmed with dog/cat example.
- B: Cosine similarity measures semantic relatedness between vectors.
- C: Vector arithmetic (addition/subtraction) reveals linguistic relationships (dog + young = puppy).
- E: The attention mechanism (used in GPT-family models) produces contextualized embeddings.
- D (Incorrect): This describes bag-of-words, NOT semantic embeddings. Embeddings specifically capture context — that's their advantage over statistical methods.

---

### Q26 — Scenario: PII Compliance (Medium)
**Correct: C — PII Detection**
The requirement is to identify and remove personal data (names, phone numbers, addresses) before storage — this is exactly the purpose of PII detection in Azure Language.
- A: Key phrase extraction identifies topics, not personal data.
- B: Sentiment analysis measures emotional tone, not personal data.
- D: Language detection identifies the language of text, not personal data.

---

### Q27 — Scenario: Multilingual Routing (Medium)
**Correct: D — Language Detection**
Before routing reviews to regional pipelines, the system must first identify the language of each review. Language detection evaluates text and returns the primary language and confidence score.
- A: NER finds entities in text — it doesn't identify language.
- B: Key phrase extraction works on content, not language identification.
- C: Sentiment analysis requires knowing the language first — it's a downstream step.

---

### Q28 — Scenario: Differentiating Articles (Medium)
**Correct: C — TF-IDF**
When simple word frequency returns the same top terms across all documents (cloud, Azure, data), TF-IDF is the solution. It penalizes words that appear across all documents and highlights terms that are distinctive to each individual article.
- A: Stop word removal alone would not solve the problem — domain-specific common words ("cloud", "Azure") would remain.
- B: TextRank summarizes a document — it doesn't differentiate between documents in a corpus.
- D: Cosine similarity compares documents but doesn't identify distinctive terms within them.

---

### Q29 — Scenario: Structured Automated Output (Challenging)
**Correct: B**
General-purpose AI models produce variable, conversational output depending on how prompts are phrased — they are not reliable for producing consistent structured JSON in automated pipelines. Azure Language in Foundry tools uses statistical, deterministic analyzers that return structured, predictable output every time.
- A: General-purpose models do NOT return structured JSON by default — output varies by prompt.
- C: Azure Bot Service is for conversational agents, not structured data extraction from text.
- D: The Foundry chat playground does not have a "JSON output mode" for all general tasks.

---

### Q30 — Scenario: TextRank Algorithm (Challenging)
**Correct: C — TextRank extractive summarization**
The scenario describes exactly the TextRank algorithm: sentences as nodes, weighted edges based on word overlap, iterative scoring, and selecting top-ranked sentences. This is the definition of TextRank extractive summarization.
- A: Bag-of-words with Naive Bayes is used for classification tasks (spam filtering, sentiment), not graph-based summarization.
- B: TF-IDF identifies important terms across documents — it doesn't build sentence graphs.
- D: Cosine similarity document clustering groups similar documents together — it doesn't produce sentence-level summaries.

---

---

## DOMAIN BREAKDOWN

| Domain | Questions Covered |
|---|---|
| Tokenization & Pre-processing | Q1, Q4, Q6, Q9, Q19, Q22 |
| Azure Language Service Capabilities | Q2, Q5, Q7, Q14, Q23, Q26, Q27 |
| Sentiment Analysis | Q3, Q20 |
| Named Entity Recognition | Q10, Q23 |
| Statistical Text Analysis (TF-IDF, Frequency) | Q11, Q12, Q13, Q24, Q28 |
| Semantic Vectors & Embeddings | Q15, Q17, Q18, Q25 |
| Summarization (TextRank / Extractive / Abstractive) | Q13, Q16, Q30 |
| Service Selection & Architecture | Q8, Q21, Q23, Q29 |
| PII Detection | Q14, Q26 |
| Language Detection | Q5, Q27 |
| General-Purpose AI vs Azure Language | Q8, Q20, Q21, Q29 |

---

## TOP 5 EXAM TAKEAWAYS

1. **General-Purpose AI Model vs Azure Language Tools** — Know when to use each. General-purpose models are flexible and conversational but probabilistic. Azure Language tools are deterministic and structured — better for automated pipelines.

2. **TF-IDF solves what simple frequency cannot** — If a word appears in every document, its IDF = 0 and it carries no discriminative weight. TF-IDF is the go-to technique for identifying what makes each document unique within a corpus.

3. **Tokenization pre-processing shapes everything downstream** — Stemming, lemmatization, stop word removal, POS tagging, and N-gram extraction all happen before analysis. Understanding what each does (and doesn't do) is essential.

4. **Semantic embeddings encode meaning as vectors** — Cosine similarity measures relatedness; vector arithmetic reveals linguistic relationships (dog + young = puppy). Modern contextualized embeddings use the attention mechanism.

5. **Know the full Azure Language feature set** — Language detection, PII detection, named entity recognition, key phrase extraction, and sentiment analysis all have distinct use cases and output formats that the exam tests by scenario.

---

## COMMON AI-900 EXAM TRAPS & MISCONCEPTIONS

⚠️ **Trap 1: Confusing stemming with lemmatization**
Stemming is fast and mechanical — it can produce non-words ("glob" from "global"). Lemmatization always produces a valid dictionary word. Exam questions often make these sound interchangeable — they are not.

⚠️ **Trap 2: Assuming general-purpose AI models always produce structured output**
They don't. Output depends on how you phrase the prompt. For deterministic, pipeline-ready output, use Azure Language tools.

⚠️ **Trap 3: Thinking TF-IDF is just "better frequency counting"**
TF-IDF is fundamentally about cross-document relevance, not just counting. A word that appears in all documents gets a TF-IDF of 0 — frequency counting would rank it highly.

⚠️ **Trap 4: Mistaking extractive for abstractive summarization**
Extractive = pulls original sentences. Abstractive = generates new text. TextRank is extractive. Modern LLMs can do both.

⚠️ **Trap 5: Confusing PII detection with NER**
Both identify entities in text. But PII detection is specifically for sensitive personal data and supports redaction for privacy compliance. NER is broader — it also finds organizations, dates, quantities, etc. — and is not designed for redaction.
