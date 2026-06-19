# Module Check-Your-Knowledge — Quick Reference
*JDA Program | Microsoft Learn AI-900 Path*
*All scores: ✅ Passed (100%)*

---

## 1. Introduction to AI-Powered Information Extraction Concepts

**Q1. Which statement accurately defines AI information extraction?**
→ ✅ Analyzing unstructured content to identify and extract relevant fields and values.

**Q2. How is OCR used in the information extraction process?**
→ ✅ Optical character recognition (OCR) converts images of text into machine-readable text data.

**Q3. How does generative AI enhance the data extraction process?**
→ ✅ By using semantic language models to accurately match extracted values to data fields.

---

## 2. Get Started with AI-Powered Information Extraction in Azure

**Q1. What is the key advantage of Azure Content Understanding over basic OCR?**
→ ✅ Azure Content Understanding understands document structure and maps extracted data to a defined schema.

**Q2. What is the primary role of an analyzer in Azure Content Understanding?**
→ ✅ It defines how content is processed and what structured data is returned.

**Q3. When using the Azure Content Understanding Python SDK, what happens after you submit content for analysis?**
→ ✅ You must poll a URL until the analysis job completes.

---

## 3. Introduction to Computer Vision Concepts

**Q1. Computer vision analyzes what kinds of values in an image?**
→ ✅ Pixels

**Q2. What is the primary role of filters in a convolutional neural network (CNN)?**
→ ✅ To extract numeric features from images for use in a neural network.

**Q3. Which description best matches a Vision Transformer (ViT)?**
→ ✅ A model that uses attention to process image patches and create contextual embeddings.

---

## 4. Get Started with Computer Vision in Azure

**Q1. What is a multimodal model?**
→ ✅ A model that can understand and work with more than one type of data, such as text and images.

**Q2. How can developers programmatically generate images using Foundry image generation models?**
→ ✅ By sending text prompts through the OpenAI Responses API using a deployed image model.

**Q3. Which value should you pass as the `model` parameter when generating images with the OpenAI Python SDK in Foundry?**
→ ✅ The deployment name you gave the image generation model in your Foundry resource.

**Q4. Why is video generation with Sora models in Foundry handled as an asynchronous job?**
→ ✅ Because video generation is resource-intensive and takes time to complete.

---

## 5. Get Started with Speech in Azure ✅ 100%

**Q1. Why would a developer use the Azure Speech-to-Text SDK instead of only the Foundry playground?**
→ ✅ The SDK allows speech recognition to be added directly into application code.

**Q2. What does the Azure Text-to-Speech SDK handle for developers?**
→ ✅ Authentication, network communication, and audio generation.

**Q3. What role does the Voice Live Python SDK (`azure-ai-voicelive`) play in a voice-enabled agent?**
→ ✅ It opens a real-time connection, streams audio, and handles spoken responses and interruptions.

---

## 6. Introduction to AI Speech Concepts ✅ 100%

**Q1. What happens during the pre-processing stage of speech recognition?**
→ ✅ Feature vectors are extracted from the audio waveform for modeling.

**Q2. What are phonemes?**
→ ✅ The smallest unit of sound in speech.

**Q3. Why is it important to generate prosody in speech synthesis?**
→ ✅ Prosody ensures natural pronunciation and speech cadence.

---

## 7. Get Started with Text Analysis in Azure ✅ 100%

**Q1. You need to analyze text where the same input must return structured results based on statistical techniques. Which approach is most appropriate?**
→ ✅ The Azure Language SDK, because it returns deterministic, structured output.

**Q2. What is the purpose of the client object in the Azure Language SDK?**
→ ✅ It helps application code communicate with the Azure Language service.

**Q3. What is the main purpose of the Azure Language MCP server?**
→ ✅ To expose Azure Language capabilities to agents through the Model Context Protocol.

---

## 8. Introduction to Natural Language Processing Concepts

**Q1. What is the purpose of tokenization?**
→ ✅ To break down text into smaller units for analysis.

**Q2. Which technique determines the importance of words in a specific document within a larger collection?**
→ ✅ TF-IDF (Term Frequency – Inverse Document Frequency)

**Q3. What best describes the role of embedding vectors in NLP?**
→ ✅ They capture semantic token relationships in multiple dimensions.

---

## 9. Get Started with Generative AI and Agents

**Q1. What best describes Foundry's model catalog?**
→ ✅ A central hub to discover, filter, compare, and test many generative AI models from multiple providers.

**Q2. Which statement best describes a foundation model in Microsoft Foundry?**
→ ✅ A large, pretrained model that provides general capabilities and can be used immediately or customized.

**Q3. What is the primary benefit of using the Model Playground before writing code?**
→ ✅ It lets you test prompts, compare models, and capture working settings that you can reuse in code.

**Q4. What is the primary outcome of publishing an agent in Microsoft Foundry?**
→ ✅ It converts the agent into a managed Azure resource with a stable endpoint you can share and integrate without exposing your Foundry project or source code.

**Q5. In the Python example, which line calls the published agent (rather than a model deployment directly)?**
→ ✅ `response = openai_client.responses.create(input=[...], extra_body={'agent': {'name': agent.name, 'type': 'agent_reference'}})`

---

## 10. Introduction to Large Language Model Concepts

**Q1. What is a large language model (LLM)?**
→ ✅ A type of AI model designed to generate human-like text.

**Q2. What is the purpose of tokenization?**
→ ✅ To break down text into smaller units.

**Q3. What are embeddings?**
→ ✅ Vector-based representations of tokens that capture their semantic meaning.

**Q4. What does an attention layer do in a transformer model?**
→ ✅ Examines the relationships between each token and the tokens around it.

**Q5. What is the purpose of a system prompt?**
→ ✅ To provide context and instructions to the AI model.

**Q6. What is an agent in the context of AI?**
→ ✅ An AI system that can perform tasks on behalf of a user.

---

## 11. Introduction to AI Concepts

**Q1. Which is the most accurate description of generative AI?**
→ ✅ Generative AI uses a language model to create original content in response to a prompt.

**Q2. What is an AI agent?**
→ ✅ An AI application that can perform tasks on behalf of a user.

**Q3. An AI application reads email aloud to a user. Which AI speech capability is being used?**
→ ✅ Speech synthesis

---

## 12. Get Started with AI in Azure

**Q1. Which statement best explains the relationship between AI and ML?**
→ ✅ AI is the overarching goal of creating systems that exhibit human-like intelligence, while ML is a data-driven method used to achieve AI by learning patterns from data.

**Q2. How does Microsoft Foundry relate to Azure?**
→ ✅ Foundry is built on top of Azure and uses Azure resources such as compute, networking, identity, and security to host and operate AI applications.

**Q3. Which statement best describes how keys, secrets, and endpoints work together in an Azure-based AI application?**
→ ✅ The endpoint is a URL for calling a deployed model, and the key (stored as a secret in Azure Key Vault) authenticates the request made to that endpoint.

**Q4. Which statement best describes a client application in the context of an AI solution built with Foundry?**
→ ✅ A client application is a program the user interacts with — such as a web app or mobile app — that sends requests to a model endpoint and displays the response.
