---
tags: [jda, generative-ai, agents, foundry, mock-test]
source:
  - "Introduction to generative AI and agents (Microsoft Learn)"
  - "Get started with generative AI and agents in Azure (Microsoft Learn)"
created: 2026-06-12
questions: 30
---

# JDA Mock Test 2 — Generative AI & Agents

**Instructions:** 30 multiple-choice questions. Pick one answer per question. Answer key is at the bottom — no peeking!

- Part 1 (Q1–16): Introduction to generative AI and agents (LLMs, prompts, agents)
- Part 2 (Q17–30): Get started with generative AI and agents in Azure (Foundry)

Related: [[JDA Mock Test]]

---

## Part 1 — Generative AI Fundamentals

**Q1.** Fundamentally, large language models (LLMs) are trained to:
- A) Translate code between programming languages
- B) Generate completions based on prompts by predicting the most probable next token
- C) Store documents in a database
- D) Compress images

**Q2.** What is the difference between an LLM and an SLM?
- A) SLMs cannot generate text
- B) SLMs are smaller, more compact language models; LLMs are larger
- C) LLMs only work offline
- D) There is no difference

**Q3.** In language models, a *token* can be:
- A) Only a complete word
- B) Only punctuation
- C) A word, a sub-word (like "un" in "unbelievable"), punctuation, or other character sequences
- D) Only a number

**Q4.** What is the first step in training a large language model?
- A) Deploying it to the cloud
- B) Tokenization — breaking training text into distinct tokens with unique integer IDs
- C) Writing system instructions
- D) Creating an API endpoint

**Q5.** Vectors that have linguistic and semantic meaning encoded into them are called:
- A) Embeddings
- B) Tokens
- C) Indexes
- D) Checksums

**Q6.** Which architecture do modern language models use, consisting of encoder and decoder blocks?
- A) Decision tree
- B) Transformer
- C) Convolutional network only
- D) Linear regression

**Q7.** What is the role of the *attention* mechanism in a transformer?
- A) It deletes irrelevant tokens permanently
- B) It determines how much each surrounding token influences the current token when computing its representation
- C) It encrypts the training data
- D) It controls GPU usage

**Q8.** Why is *positional encoding* fed into the transformer along with token vectors?
- A) To track GPS location
- B) Because the order in which tokens appear in a sequence affects how they relate to each other
- C) To count how many users are online
- D) To sort tokens alphabetically

**Q9.** Tokens with similar meanings (like "dog" and "puppy") end up with embedding vectors that:
- A) Point in similar directions in vector space
- B) Are always identical
- C) Point in opposite directions
- D) Have no relationship

**Q10.** Which measure is used to determine how semantically close two embedding vectors are?
- A) Standard deviation
- B) Cosine similarity
- C) Pixel distance
- D) Word count

**Q11.** During decoder training, the technique where tokens *after* the current token are ignored is called:
- A) Dropout
- B) Masked attention
- C) Backpropagation
- D) Gradient descent

**Q12.** Which of the following makes a prompt MORE effective?
- A) Being as vague as possible
- B) Providing clear instructions, relevant context, and examples of the desired output
- C) Using only one-word prompts
- D) Avoiding any mention of the desired format

**Q13.** Including a few worked examples in your prompt to show the model the pattern you want is called:
- A) Zero-shot prompting
- B) Few-shot prompting
- C) Fine-tuning
- D) Tokenization

**Q14.** What is a *system message / system instruction* used for?
- A) Displaying error messages to users
- B) Defining the model's role, behavior, style, constraints, and output rules
- C) Restarting the model
- D) Storing user passwords

**Q15.** What distinguishes an AI *agent* from simply chatting with a model?
- A) Agents are always free
- B) Agents combine a model with instructions and tools so they can take actions and automate multi-step tasks
- C) Agents don't use prompts
- D) Agents can't access external data

**Q16.** Which of the following is something agents can do? *(per the module)*
- A) Break goals into structured steps and call external tools automatically
- B) Physically repair hardware
- C) Train themselves on new data without any setup
- D) Replace the need for any human oversight

---

## Part 2 — Generative AI & Agents in Azure (Foundry)

**Q17.** An agent in Microsoft Foundry packages together which three things?
- A) A database, a website, and a spreadsheet
- B) A model, instructions (system prompt), and tools
- C) A virtual machine, a firewall, and a load balancer
- D) Python, JavaScript, and C#

**Q18.** In Foundry, the difference between **Tools** and **Knowledge** is:
- A) Tools = context, Knowledge = actions
- B) Tools = actions the agent can take; Knowledge = context/content the agent can retrieve
- C) They are identical
- D) Knowledge is only for images

**Q19.** Which technique lets an agent retrieve relevant content from your documents or datasets to ground its answers?
- A) Reinforcement learning
- B) Retrieval-augmented generation (RAG)
- C) Data mirroring
- D) Tokenization

**Q20.** When a Foundry agent answers using a knowledge source, the response includes:
- A) A citation for the knowledge store it used
- B) The full source code of the agent
- C) An invoice
- D) The model's training data

**Q21.** Which of these is an example of a tool an agent might use?
- A) Code Interpreter for data analysis and file handling
- B) A monitor's brightness setting
- C) The Azure invoice page
- D) A keyboard shortcut

**Q22.** Where can you centrally discover and manage tools for agents in Foundry?
- A) The Foundry Tool Catalog
- B) Windows Task Manager
- C) The Azure pricing calculator
- D) Microsoft Word

**Q23.** Where do you browse and compare available models before deploying one in Foundry?
- A) The model catalog
- B) The billing dashboard
- C) Visual Studio
- D) The resource group list

**Q24.** What is the Foundry Playground used for when building an agent?
- A) Hosting production traffic
- B) Testing and refining the agent — validating prompts, behavior, and settings before using it in code
- C) Managing user accounts
- D) Designing logos

**Q25.** To call an agent programmatically with the Project API, you need to find its:
- A) IP address
- B) agent-id (visible in the Playground's code view / .env variables)
- C) MAC address
- D) Credit card number

**Q26.** In the Python sample, which SDK class is used to connect to a Foundry project?
- A) `AIProjectClient` from `azure.ai.projects`
- B) `pandas.DataFrame`
- C) `numpy.array`
- D) `FoundryBot`

**Q27.** Which credential approach does the sample code use to authenticate to the Foundry project?
- A) Hard-coded password in the script
- B) `DefaultAzureCredential` from `azure-identity` (Microsoft Entra ID)
- C) No authentication at all
- D) A CAPTCHA

**Q28.** What happens when you **publish** an agent in Foundry?
- A) It is posted publicly on social media
- B) It becomes a managed Azure resource with its own dedicated, stable endpoint that can be shared without exposing the project or source code
- C) It is deleted from the project
- D) It stops working in the Playground

**Q29.** Can you use an agent's endpoint *without* publishing it?
- A) No, publishing is always required
- B) Yes — but then you're using it as a development asset inside the project, which is fine for iteration but not ideal for distribution and governance
- C) Yes, and it behaves identically to a published agent in every way
- D) Only on weekends

**Q30.** The Project API enables you to: *(best answer)*
- A) Only delete projects
- B) Integrate agents into apps, orchestrate multi-step tasks, pass structured inputs, and run agents at scale
- C) Change your Azure subscription billing address
- D) Render 3D graphics

---

## ✅ Answer Key

| Q   | Ans | Q   | Ans | Q   | Ans |
| --- | --- | --- | --- | --- | --- |
| 1   | B   | 11  | B   | 21  | A   |
| 2   | B   | 12  | B   | 22  | A   |
| 3   | C   | 13  | B   | 23  | A   |
| 4   | B   | 14  | B   | 24  | B   |
| 5   | A   | 15  | B   | 25  | B   |
| 6   | B   | 16  | A   | 26  | A   |
| 7   | B   | 17  | B   | 27  | B   |
| 8   | B   | 18  | B   | 28  | B   |
| 9   | A   | 19  | B   | 29  | B   |
| 10  | B   | 20  | A   | 30  | B   |

---

## Scoring

- **27–30** → Excellent, ready for the module assessments
- **21–26** → Good, review the questions you missed
- **Below 21** → Re-read the weak units, then retake the test

## Sources

- [Introduction to generative AI and agents](https://learn.microsoft.com/en-us/training/modules/fundamentals-generative-ai/)
- [Get started with generative AI and agents in Azure](https://learn.microsoft.com/en-us/training/modules/get-started-with-generative-ai-and-agents/)

*Track your attempts:*

| Date | Score | Notes |
|------|-------|-------|
|      | /30   |       |
