# AI-900 ExamTopics — Questions & Answers
*Source: ExamTopics AI-900 Topic 1 | 125 Questions*
*Format: Question → Options → Correct Answer → Why*

---

## Q1
A company develops a webchat bot to provide automated answers to common customer queries. Which business benefit should the company expect?

- A. increased sales
- B. a reduced workload for the customer service agents
- C. improved product reliability

**✅ B**
A webchat bot handles common queries automatically, directly reducing the volume of work that human agents need to handle.

---

## Q2
For a machine learning process, how should you split data for training and evaluation?

- A. Use features for training and labels for evaluation
- B. Randomly split the data into rows for training and rows for evaluation
- C. Use labels for training and features for evaluation
- D. Randomly split the data into columns for training and columns for evaluation

**✅ B**
Data is split row-wise so each subset contains all features and labels. Splitting by columns would break the relationship between features and their labels.

---

## Q3 *(Hotspot — Confusion Matrix)*
Given a confusion matrix, identify the True Positive count and the False Negative count.

**✅ TP = 11 | FN = 1033**
True Positives are cases correctly predicted as positive. False Negatives are cases that were actually positive but predicted as negative. Read the matrix with Actual on one axis and Predicted on the other.

---

## Q4
You build a model using AutoML. You need to ensure the model meets the Microsoft **transparency** principle for responsible AI. What should you do?

- A. Set Validation type to Auto
- B. Enable Explain best model
- C. Set Primary metric to accuracy
- D. Set Max concurrent iterations to 0

**✅ B**
Transparency means AI systems should be understandable. Enabling model explanation opens the "black box" so developers and users can see which features drove the prediction and why.

---

## Q5 *(Hotspot — Yes/No)*
Predicting the price of a house = anomaly detection? | Detecting a sudden spike in network traffic = anomaly detection? | Predicting whether a patient will develop diabetes = anomaly detection?

**✅ No / Yes / No**
- Price prediction = regression (continuous numeric output)
- Sudden spike detection = anomaly detection (identifying outliers)
- Diabetes prediction = classification (binary yes/no outcome with labeled data)

---

## Q6 *(Hotspot)*
An AI system for an autonomous vehicle must function reliably in normal and unexpected conditions. This requirement relates to which responsible AI principle?

**✅ Reliability and safety**
Reliability and safety requires AI systems to perform consistently, respond safely to unanticipated conditions, and resist harmful manipulation.

---

## Q7 *(Drag and Drop — AI Workloads)*
Match workloads: chatbot / recycling machine that identifies bottles / analyzing customer feedback text

**✅ Conversational AI / Computer Vision / Natural Language Processing**
- Chatbot = conversational AI
- Identifying objects in images = computer vision
- Analyzing sentiment or topics in text = NLP

---

## Q8
You are designing an AI system that empowers people with hearing, visual, and other impairments. This is an example of which responsible AI principle?

- A. fairness
- B. inclusiveness
- C. reliability and safety
- D. accountability

**✅ B**
Inclusiveness means AI should benefit everyone, including people with disabilities. Fairness is about avoiding bias across demographic groups — different from designing for accessibility.

---

## Q9 *(Drag and Drop — Responsible AI)*
Match: "AI systems should operate consistently under normal and unexpected conditions" / "People who design AI systems must answer for how they operate" / "Personal data must be secured and protected"

**✅ Reliability and safety / Accountability / Privacy and security**
- Consistent, safe operation under all conditions = reliability and safety
- Humans answerable for AI behavior = accountability
- Protecting personal data = privacy and security

---

## Q10 *(Hotspot)*
An AI system must be able to resist manipulation and respond safely to edge cases. Which responsible AI principle does this relate to?

**✅ Reliability and safety**
Resilience to manipulation and safe behavior in unexpected situations are core attributes of reliability and safety.

---

## Q11
You are building an AI system. Which task ensures the service meets the Microsoft **transparency** principle?

- A. Ensure all visuals have associated text for screen readers
- B. Enable autoscaling based on demand
- C. Provide documentation to help developers debug code
- D. Ensure the training dataset is representative of the population

**✅ C**
Transparency means making AI understandable. Documentation that explains how the system works and helps developers understand its behavior directly supports transparency. Option A is inclusiveness; D is fairness.

---

## Q12 *(Drag and Drop — AI Workloads)*
Match: predicting sales figures / grouping customers by behavior / determining if a loan application is approved or not

**✅ Regression / Clustering / Classification**
- Predicting a numeric value = regression
- Grouping by similarity without predefined labels = clustering
- Yes/no binary output = classification

---

## Q13
A company is exploring voice recognition in smart home devices and wants to identify barriers that might unintentionally exclude specific user groups. Which responsible AI principle does this represent?

- A. accountability
- B. fairness
- C. inclusiveness
- D. privacy and security

**✅ C**
Inclusiveness is specifically about identifying and removing barriers that could unintentionally exclude people from using AI systems.

---

## Q14
What are three Microsoft guiding principles for responsible AI?

- A. knowledgeability
- B. decisiveness
- C. inclusiveness
- D. fairness
- E. opinionatedness
- F. reliability and safety

**✅ C, D, F**
The six responsible AI principles are: Fairness, Reliability and Safety, Privacy and Security, Inclusiveness, Transparency, and Accountability. Only C, D, and F appear in this list.

---

## Q15 *(Hotspot)*
Returning the bounding box coordinates for each object found in an image is an example of which computer vision capability?

**✅ Object detection**
Object detection identifies what objects are present AND returns their pixel coordinates as bounding boxes. Image classification only labels the whole image without locating objects.

---

## Q16 *(Hotspot)*
The process of creating new features from raw data to help machine learning algorithms learn better is called:

**✅ Feature engineering**
Feature engineering transforms raw data into more meaningful inputs. Feature selection chooses from existing features; feature engineering creates new ones (e.g., extracting "day of week" from a timestamp).

---

## Q17
You run a charity event posting photos of people wearing sunglasses on Twitter. You need to retweet only photos that include faces AND at least one person wearing sunglasses. What should you use?

- A. the Verify operation in the Face service
- B. the Detect operation in the Face service
- C. the Describe Image operation in Computer Vision
- D. the Analyze Image operation in Computer Vision

**✅ B**
The Face Detect operation returns detected faces along with facial attributes including whether the person is wearing glasses. Verify checks if two faces belong to the same person — not relevant here.

---

## Q18
When designing an AI loan approval system, the factors used to make the decision should be explainable. Which responsible AI principle does this represent?

- A. transparency
- B. inclusiveness
- C. fairness
- D. privacy and security

**✅ A**
Transparency means AI systems should be understandable — users and regulators should be able to understand how and why a decision was made. The keyword "explainable" maps directly to transparency.

---

## Q19 *(Hotspot — Yes/No)*
Transparency helps teams understand how a model was created → Yes/No? | A health insurance bot that prioritizes claims based on severity violates privacy and security → Yes/No? | Offering different service pricing to make AI accessible is an example of inclusiveness → Yes/No?

**✅ Yes / No / No**
- Understanding how a model was built = transparency ✅
- Prioritizing claims = relates to fairness or accountability, not privacy
- Pricing tiers without reference to excluded groups = not clearly inclusiveness in this context

---

## Q20 *(Drag and Drop — Responsible AI)*
Match: "AI should not discriminate based on gender, race, or religion" / "Personal data must be protected and users must have control" / "Users should be able to understand why a decision was made"

**✅ Fairness / Privacy and security / Transparency**

---

## Q21 *(Drag and Drop — ML Pipeline Sequence)*
What are the three processes to perform IN ORDER before deploying a model?

**✅ Data preparation → Train model → Evaluate model**
You must clean and prepare data first, then train the model on it, then evaluate its performance before deployment.

---

## Q22
You are building an AI app and need to follow responsible AI principles. Which two should you implement?

- A. Implement Agile methodology
- B. Implement AI model validation as part of the software review process
- C. Establish a risk governance committee including legal and privacy officers
- D. Prevent disclosure of AI-based algorithms for automated decision making

**✅ B, C**
Model validation (B) supports reliability and safety. A governance committee (C) supports accountability and privacy. Agile (A) is a development methodology, not a responsible AI principle. Preventing disclosure (D) contradicts transparency.

---

## Q23 *(Hotspot)*
An AI hiring tool produces results that are influenced by gender bias in the training data. Which responsible AI principle is most at risk?

**✅ Fairness**
Fairness requires AI systems not to discriminate or produce biased outcomes based on gender, race, religion, or other protected characteristics.

---

## Q24 *(Drag and Drop — ML Tasks)*
Match: "outputting a confusion matrix with TP, FP, TN, FN" / "using domain knowledge to create new input columns from raw data" / "selecting only the most relevant subset of input columns"

**✅ Model evaluation / Feature engineering / Feature selection**

---

## Q25 *(Hotspot)*
In a machine learning dataset, the columns used as inputs to predict an outcome are called:

**✅ Features**
Features are the input variables (independent variables) used to train the model. Labels are the outputs (what you want to predict).

---

## Q26
You have a Predicted vs. True chart. Which type of model is this chart used to evaluate?

- A. classification
- B. regression
- C. clustering

**✅ B**
A Predicted vs. True chart plots continuous numeric predicted values against actual values. The closer the points fall to the y=x line, the better the model. This chart is specific to regression.

---

## Q27
Which type of machine learning should you use to predict the number of gift cards that will be sold next month?

- A. classification
- B. regression
- C. clustering

**✅ B**
Predicting a numeric count is a regression task. Classification outputs a category; clustering groups unlabeled data.

---

## Q28
You train a model to predict taxi fares. What should you use as a feature?

- A. the number of taxi journeys in the dataset
- B. the trip distance of individual taxi journeys
- C. the fare of individual taxi journeys
- D. the trip ID of individual taxi journeys

**✅ B**
Trip distance is an input variable that influences the fare — it is a feature. The fare itself is the label (what you're predicting). Trip ID and total journey count don't influence fare.

---

## Q29
You need to predict the sea level in meters for the next 10 years. Which machine learning type should you use?

- A. classification
- B. regression
- C. clustering

**✅ B**
Sea level in meters is a continuous numeric value — predicting it is a regression task.

---

## Q30 *(Hotspot — Yes/No)*
AutoML automates the selection of algorithms and hyperparameters → Yes/No? | AutoML requires you to manually select the algorithm → Yes/No? | AutoML tries multiple algorithms in parallel and selects the best → Yes/No? | AutoML automatically defines the label column → Yes/No?

**✅ Yes / No / Yes / No**
AutoML automates algorithm selection and hyperparameter tuning. You still must supply the dataset and specify the label column. It does NOT require manual algorithm selection, and it does NOT automatically determine the label.

---

## Q31 *(Hotspot)*
A bank wants to predict whether a loan will be repaid or not. Which ML type should be used?

**✅ Classification**
Repaid or not repaid is a binary (yes/no) outcome — this is two-class classification. Regression would be used to predict a numeric amount; clustering groups unlabeled data.

---

## Q32 *(Hotspot — Yes/No)*
Labeling data means adding the answer (output) you want the model to predict → Yes/No? | Training data and test data must come from completely different original datasets → Yes/No? | Accuracy is always the best metric for evaluating a classifier → Yes/No?

**✅ Yes / No / No**
- Labeling = marking outputs for supervised learning ✅
- Training/test data typically come from the same original dataset, split by rows ❌
- Accuracy fails on imbalanced datasets; precision, recall, F1, and AUC are often better ❌

---

## Q33
Which service should you use to extract text, key/value pairs, and table data automatically from scanned documents?

- A. Form Recognizer
- B. Text Analytics
- C. Language Understanding
- D. Custom Vision

**✅ A**
Form Recognizer (now Azure AI Document Intelligence) is specifically designed to extract structured fields, key-value pairs, and tables from documents like invoices, receipts, and forms.

---

## Q34 *(Hotspot)*
Which Azure service extracts text, key/value pairs, and tables from forms and documents?

**✅ Form Recognizer**
Form Recognizer applies machine learning to extract structured data from semi-structured documents. OCR only extracts raw text without semantic field mapping.

---

## Q35
You publish an inference pipeline in Azure ML Designer. Which two parameters do you need to consume it?

- A. the model name
- B. the training endpoint
- C. the authentication key
- D. the REST endpoint

**✅ C, D**
To call a published pipeline, you need the REST endpoint URL (where to send requests) and the authentication key (to prove you're authorized). The model name and training endpoint are not needed for consumption.

---

## Q36 *(Hotspot)*
To perform real-time inferencing from Azure ML Designer, you must deploy to which compute type?

**✅ Azure Kubernetes Service (AKS)**
Real-time endpoints in Azure ML must be deployed to AKS for production. Azure Container Instances (ACI) can be used for testing/development only.

---

## Q37 *(Hotspot)*
Which ML type is used to predict a numeric value such as annual household income?

**✅ Regression**
Predicting a continuous numeric value = regression. Classification predicts a category; clustering groups data without predefined labels.

---

## Q38 *(Hotspot — Yes/No)*
Azure ML Designer lets you connect datasets and modules on a canvas → Yes/No? | You can save progress as a pipeline draft in Designer → Yes/No? | You can add custom Java code modules in Designer → Yes/No?

**✅ Yes / Yes / No**
Designer supports Python and R custom code modules but not Java. Drag-and-drop of datasets and modules, and saving as a draft, are both supported features.

---

## Q39 *(Hotspot)*
In a house price prediction dataset: what are "Household Income" and "House Price Category"?

**✅ Household Income = Feature | House Price Category = Label**
Features are inputs the model uses to make a prediction. The label is what you are trying to predict (the output).

---

## Q40 *(Hotspot)*
Which Azure ML tool allows you to visually create machine learning pipelines by dragging and dropping modules on an interactive canvas?

**✅ Azure Machine Learning designer**

---

## Q41 *(Hotspot — Yes/No)*
Automated ML allows you to insert custom Python code during training → Yes/No? | Automated ML is a no-code/low-code approach to training models → Yes/No? | Automated ML uses a visual canvas to connect modules → Yes/No?

**✅ No / Yes / No**
AutoML is a no-code tool — you supply the dataset and label, and it handles algorithm selection automatically. Python code and visual canvases are features of Designer, not AutoML.

---

## Q42
A medical project uses labeled brain scan images categorized into predefined hemorrhage types. Which ML type supports early detection?

- A. clustering
- B. regression
- C. classification

**✅ C**
The data has predefined labels (hemorrhage types) — this is supervised classification. Clustering is unsupervised and doesn't use predefined categories.

---

## Q43
When training a model, why should you randomly split rows into separate subsets?

- A. to train the model twice to attain better accuracy
- B. to train multiple models simultaneously
- C. to test the model using data that was not used to train it

**✅ C**
Splitting creates a test set the model has never seen, giving an unbiased evaluation of real-world performance. Training on all data would give artificially optimistic accuracy results.

---

## Q44
Which two tasks require an enterprise workspace in Azure Machine Learning? *(Note: Enterprise workspace is deprecated — both features now available in Basic)*

- A. GUI-based AutoML experiments
- B. Create a compute instance
- C. GUI-based Designer experiments
- D. Create a dataset from a CSV

**✅ A, C** *(historical answer — enterprise workspace was retired Sept 2020)*

---

## Q45
You need to predict a customer's income range. Which two fields should you use as features?

- A. Education Level
- B. Last Name
- C. Age
- D. Income Range
- E. First Name

**✅ A, C**
Education Level and Age are meaningful predictors of income. Income Range is the label (what you're predicting). First and Last Name have no causal relationship with income.

---

## Q46
You are building a tool to identify competitors' products in retail images using a custom model. Which service should you use?

- A. Custom Vision
- B. Form Recognizer
- C. Face
- D. Computer Vision

**✅ A**
Custom Vision lets you train a model on your own labeled images to detect custom objects — competitors' products that no general model would recognize. Computer Vision uses pre-built general-purpose models.

---

## Q47 *(Hotspot — Yes/No)*
Clustering can be used to identify relationships in a dataset → Yes/No? | Regression predicts a numeric value from related features → Yes/No? | Grouping patients by disease severity (mild/moderate/severe) is clustering → Yes/No?

**✅ Yes / Yes / No**
Grouping into predefined severity categories (mild/moderate/severe) with known labels is classification, not clustering. Clustering groups data into naturally occurring groups without predefined labels.

---

## Q48 *(Hotspot — Yes/No)*
The validation dataset is the same as the test dataset → Yes/No? | A validation dataset is used to tune model hyperparameters during training → Yes/No? | The validation dataset provides an unbiased evaluation of the final model → Yes/No?

**✅ No / Yes / No**
The validation set is used during training to tune hyperparameters. The test set is separate and held back to give an unbiased final evaluation. They are not the same.

---

## Q49
What are two metrics you can use to evaluate a regression model?

- A. coefficient of determination (R²)
- B. F1 score
- C. root mean squared error (RMSE)
- D. area under curve (AUC)
- E. balanced accuracy

**✅ A, C**
R² and RMSE measure how well a regression model fits numeric data. F1, AUC, and balanced accuracy are classification metrics. Memory trick: regression metrics start with "R" (R², RMSE).

---

## Q50 *(Hotspot)*
Which ML type is used to predict the number of hours of sunlight in a day based on historical weather data?

**✅ Regression**
Hours of sunlight is a continuous numeric output — predicting it is regression.

---

## Q51 *(Drag and Drop — Designer Pipeline)*
In an automobile price prediction pipeline in Designer, which modules go in each step?

**✅ Select Columns in Dataset → Split Data → Linear Regression**
- Select Columns removes irrelevant features
- Split Data creates training and test sets
- Linear Regression is the algorithm (predicting numeric price)

---

## Q52
Which type of machine learning should you use to identify groups of people with similar purchasing habits?

- A. classification
- B. regression
- C. clustering

**✅ C**
Grouping by similarity without predefined categories = clustering. The keyword "groups" signals clustering. Classification needs predefined labels; regression predicts numbers.

---

## Q53 *(Hotspot)*
Which ML type is used to predict the sale price of a house?

**✅ Regression**
House sale price is a continuous numeric value — predicting it is regression.

---

## Q54
Which metric can you use to evaluate a classification model?

- A. true positive rate
- B. mean absolute error (MAE)
- C. coefficient of determination (R²)
- D. root mean squared error (RMSE)

**✅ A**
True positive rate (also called recall or sensitivity) is a classification metric. MAE, R², and RMSE are regression metrics that measure error in numeric predictions.

---

## Q55
Which two components can you drag onto a canvas in Azure ML Designer?

- A. dataset
- B. compute
- C. pipeline
- D. module

**✅ A, D**
Designer lets you drag datasets (data sources) and modules (processing steps/algorithms) onto the canvas to build pipelines visually.

---

## Q56
You need to create a training dataset and validation dataset from an existing dataset. Which Designer module should you use?

- A. Select Columns in Dataset
- B. Add Rows
- C. Split Data
- D. Join Data

**✅ C**
The Split Data module divides a dataset into two subsets by rows — one for training and one for validation/testing.

---

## Q57 *(Drag and Drop — ML Types)*
Match: "predict the annual revenue of a new store" / "segment customers into groups for marketing" / "predict whether a student will complete a university course"

**✅ Regression / Clustering / Classification**
- Predicting annual revenue (a number) = regression
- Segmenting into groups without predefined labels = clustering
- Will complete or not (yes/no) = classification

---

## Q58 *(Hotspot)*
In Custom Vision object detection, the probability score returned alongside a bounding box represents what?

**✅ Confidence**
The confidence score indicates how certain the model is that its prediction is correct. It is not accuracy (a model-level metric calculated over many predictions).

---

## Q59 *(Hotspot)*
Which responsible AI principle requires that AI design consider all human races, experiences, and capabilities?

**✅ Inclusiveness**
Inclusiveness ensures AI benefits everyone — including people with disabilities and people from all backgrounds and demographics.

---

## Q60 *(Hotspot)*
The process of normalizing or scaling numeric input columns to ensure they are on a comparable range is part of which ML step?

**✅ Feature engineering**
Scaling and normalization transform raw feature values to improve model performance. This falls under feature engineering (creating better inputs from raw data).

---

## Q61 *(Hotspot)*
The process of adding tags or annotations to raw data to indicate the correct output (e.g., marking images as "cat" or "dog") is called:

**✅ Labelling**
Labelling is the process of annotating data with the correct target output so supervised learning models can learn from it.

---

## Q62
A recycling machine must automatically identify bottles of the correct shape and reject all others. Which AI workload should be used?

- A. anomaly detection
- B. conversational AI
- C. computer vision
- D. natural language processing

**✅ C**
Identifying objects by their visual shape in images/video is computer vision. Anomaly detection works on time-series data; it does not analyze images.

---

## Q63 *(Hotspot — Yes/No)*
When creating a Custom Vision project with type "Object Detection," you must choose a classification type (MultiClass or MultiLabel) → Yes/No? | Custom Vision allows you to label images and train a custom model → Yes/No? | Custom Vision can analyze video files directly → Yes/No?

**✅ No / Yes / Yes**
- Classification type selection is only for Classification projects, not Object Detection ❌
- Custom Vision lets you upload labeled images and train a model ✅
- Custom Vision can process video for object detection ✅

---

## Q64
In which two scenarios can you use Form Recognizer?

- A. Extract the invoice number from an invoice
- B. Translate a form from French to English
- C. Find images of products in a catalog
- D. Identify the retailer from a receipt

**✅ A, D**
Form Recognizer extracts structured fields from documents like invoices and receipts. Translation is done by Azure Translator; image search is computer vision.

---

## Q65 *(Hotspot — Yes/No)*
The Azure Face service can locate human faces in photos → Yes/No? | The Azure Face service can compare two face images to determine if they are the same person → Yes/No? | The Azure Computer Vision service can identify a specific named person from a photo → Yes/No?

**✅ Yes / Yes / No**
- Face detection (locating faces) = Face API ✅
- Face verification (same person comparison) = Face API ✅
- Identifying a named individual = requires Face API with a trained Person Group, NOT the general Computer Vision service ❌

---

## Q66
You need to develop a mobile app for employees to scan and store their expenses while travelling. Which computer vision capability should you use?

- A. semantic segmentation
- B. image classification
- C. object detection
- D. optical character recognition (OCR)

**✅ D**
Scanning expense receipts means extracting printed text (amounts, dates, vendor names) from images — that is OCR. Form Recognizer would be even better, but OCR is the correct choice from these options.

---

## Q67 *(Hotspot — Yes/No)*
The Custom Vision service can be used for object detection → Yes/No? | You must provide labeled training images to train a Custom Vision model → Yes/No? | The Custom Vision service can analyze video files → Yes/No?

**✅ Yes / Yes / No**
Custom Vision supports both classification and object detection with user-labeled images. It works on graphic/image files, not video files directly.

---

## Q68
You are processing photos of race runners and need to read the numbers on their shirts to identify them. Which computer vision capability should you use?

- A. facial recognition
- B. optical character recognition (OCR)
- C. semantic segmentation
- D. object detection

**✅ B**
Reading numbers printed on shirts is extracting text from an image — that is OCR.

---

## Q69 *(Drag and Drop — Computer Vision)*
Match: "assign a single label to a whole image" / "locate and identify multiple objects with bounding boxes" / "label every individual pixel in an image with its object class"

**✅ Image classification / Object detection / Semantic segmentation**

---

## Q70
You use drones to identify where weeds grow between rows of crops to send removal instructions. Which computer vision capability is this?

- A. object detection
- B. OCR
- C. scene segmentation

**✅ A**
Locating weeds in specific positions within an image and returning their coordinates is object detection. OCR reads text; scene segmentation analyzes video transitions.

---

## Q71 *(Drag and Drop — Face Recognition Tasks)*
Match: "check if two face images belong to the same person" / "find which stored faces look most similar to a given face" / "divide a set of unknown faces into groups based on similarity" / "identify who a detected face belongs to within a known database"

**✅ Verification / Find similar / Grouping / Identification**
- Verification = are these two faces the same person?
- Find similar = which stored faces look like this one?
- Grouping = cluster unknown faces by similarity
- Identification = who is this person from a known group?

---

## Q72 *(Drag and Drop — Computer Vision Workloads)*
Match: "match a detected face to a known individual in a database" / "extract printed text from a scanned document" / "locate and label multiple objects in an image with bounding boxes"

**✅ Facial recognition / OCR / Object detection**

---

## Q73
You need to determine the location of cars in an image to estimate the distance between them. Which computer vision capability should you use?

- A. OCR
- B. object detection
- C. image classification
- D. face detection

**✅ B**
Object detection returns both the label ("car") and the bounding box coordinates (pixel location) for each object — exactly what's needed to estimate distances between cars.

---

## Q74 *(Hotspot)*
Which Azure service allows you to train a custom image classifier using your own labeled images?

**✅ Custom Vision**
Custom Vision lets you upload labeled images and train a model tailored to your specific categories. Computer Vision uses Microsoft's prebuilt general-purpose models and cannot be trained on custom data.

---

## Q75
You receive an annotated image from a Computer Vision API showing multiple labeled objects each with a bounding box. Which computer vision capability was used?

- A. object detection
- B. semantic segmentation
- C. OCR
- D. image classification

**✅ A**
Bounding boxes around labeled objects = object detection. Classification labels the whole image; segmentation labels pixels; OCR reads text.

---

## Q76
What are two tasks that the Computer Vision service can perform?

- A. Train a custom image classification model
- B. Detect faces in an image
- C. Recognize handwritten text
- D. Translate the text in an image between languages

**✅ B, C**
Computer Vision can detect faces (basic face analysis) and recognize printed/handwritten text via OCR. Training custom models requires Custom Vision; translation requires Azure Translator.

---

## Q77
What is a use case for classification?

- A. predicting how many cups of coffee a person will drink based on hours of sleep
- B. analyzing image contents and grouping images by similar colors
- C. predicting whether someone uses a bicycle to commute based on distance from home
- D. predicting how many minutes it will take to run a race based on past times

**✅ C**
Predicting yes/no (uses bicycle or not) = classification. Options A and D predict numeric values (regression); B groups data by similarity without labels (clustering).

---

## Q78
What are two tasks that can be performed using computer vision?

- A. predict stock prices
- B. detect brands in an image
- C. detect the color scheme in an image
- D. translate text between languages
- E. extract key phrases

**✅ B, C**
Computer Vision can identify commercial brands and analyze color schemes in images. Stock price prediction is ML regression; translation is NLP; key phrase extraction is NLP/Text Analytics.

---

## Q79
You need to build an image tagging solution for social media that tags images of your friends automatically. Which Azure service should you use?

- A. Face
- B. Form Recognizer
- C. Text Analytics
- D. Computer Vision

**✅ A**
Automatically identifying specific known individuals in photos (tagging friends) requires the Face API with enrolled Person Groups. Computer Vision provides general face detection but not identification.

---

## Q80
In which two scenarios can you use Form Recognizer?

- A. Identify the retailer from a receipt
- B. Translate from French to English
- C. Extract the invoice number from an invoice
- D. Find images of products in a catalog

**✅ A, C**
Form Recognizer extracts specific fields from structured documents like receipts and invoices. Translation = Azure Translator; image search = Computer Vision.

---

## Q81
You need to identify the main talking points in a collection of documents. Which NLP capability should you use?

- A. entity recognition
- B. key phrase extraction
- C. sentiment analysis
- D. language detection

**✅ B**
Key phrase extraction identifies the most important concepts and topics in text. The phrase "main talking points" directly maps to key phrase extraction.

---

## Q82
In which two scenarios can you use speech recognition?

- A. an in-car system that reads text messages aloud
- B. providing closed captions for recorded or live videos
- C. creating an automated public address system
- D. creating a transcript of a telephone call or meeting

**✅ B, D**
Speech recognition = speech-to-text (audio → written text). Captions and transcripts are both speech-to-text outputs. Options A and C are text-to-speech (speech synthesis) — converting text into audio output.

---

## Q83 *(Hotspot)*
Which speech AI capability converts audio from a call center recording into written text?

**✅ Speech recognition**
Speech recognition (speech-to-text) converts audio into text. Speech synthesis is the reverse — it converts text into audio.

---

## Q84
You need to build an app that reads recipe instructions aloud to support users with reduced vision. Which service should you use?

- A. Text Analytics
- B. Translator
- C. Speech
- D. Language Understanding (LUIS)

**✅ C**
Reading text aloud = text-to-speech = speech synthesis, which is a capability of the Azure Speech service. Text Analytics analyzes text; Translator translates between languages; LUIS understands user intent.

---

## Q85 *(Hotspot — Yes/No)*
The Azure Speech service can transcribe audio into text → Yes/No? | The Azure Speech service can extract named entities from a transcription → Yes/No? | The Azure Speech service can translate spoken audio from one language to another → Yes/No?

**✅ Yes / Yes / Yes**
Azure Speech covers: speech-to-text (transcription), entity extraction from transcriptions, and real-time speech translation across 30+ languages.

---

## Q86
Your website has a chatbot and you need to detect when a customer is upset based on what they type. Which AI workload should you use?

- A. anomaly detection
- B. computer vision
- C. regression
- D. natural language processing

**✅ D**
Detecting emotional tone (upset vs. calm) in written text is sentiment analysis — a core NLP capability.

---

## Q87
You plan to develop a bot that will let users query a knowledge base using natural language. Which two services should you include?

- A. QnA Maker
- B. Azure Bot Service
- C. Form Recognizer
- D. Anomaly Detector

**✅ A, B**
QnA Maker creates the knowledge base of question-and-answer pairs; Azure Bot Service provides the conversational interface to deliver those answers to users. Form Recognizer and Anomaly Detector serve different purposes.

---

## Q88
In which two scenarios can you use speech synthesis?

- A. an automated voice that reads back a credit card number entered via keypad
- B. generating live captions for a news broadcast
- C. extracting key phrases from an audio recording
- D. an AI character in a game that speaks audibly to a player

**✅ A, D**
Speech synthesis = text-to-speech (generating audio from text). Reading back numbers (A) and a speaking game character (D) both convert text to audio. Captions (B) = speech recognition; key phrase extraction (C) = NLP.

---

## Q89 *(Hotspot — Yes/No)*
The Azure Translator service can translate text between languages → Yes/No? | The Azure Translator service can transliterate text from one script to another → Yes/No? | The Azure Speech service can transcribe audio into text → Yes/No?

**✅ Yes / Yes / Yes**
Translator supports text translation and transliteration (e.g., Arabic script to Latin). The Speech service supports speech-to-text transcription.

---

## Q90 *(Drag and Drop — NLP Tasks)*
Match: "scan news to find articles mentioning specific companies or people" / "classify whether an article about a company is positive or negative"

**✅ Entity recognition / Sentiment analysis**
- Finding mentions of specific companies = named entity recognition (NER)
- Determining if content is positive or negative = sentiment analysis

---

## Q91
Which file format can you use to populate a QnA Maker knowledge base?

- A. PPTX
- B. XML
- C. ZIP
- D. PDF

**✅ D**
QnA Maker supports PDF, DOC, TXT, and TSV files. PPTX is a presentation format; XML and ZIP cannot be directly ingested.

---

## Q92
In which scenario should you use key phrase extraction?

- A. identifying whether restaurant reviews are positive or negative
- B. generating captions for a video
- C. identifying which documents cover the same topics
- D. translating documents from English to German

**✅ C**
Key phrase extraction identifies the main concepts in text. Comparing key phrases across documents reveals which ones cover similar topics. Option A = sentiment analysis; B = speech synthesis/captioning; D = translation.

---

## Q93
You have insurance claim reports stored as text and need to extract key terms to generate summaries. Which AI workload should you use?

- A. natural language processing
- B. conversational AI
- C. anomaly detection
- D. computer vision

**✅ A**
Extracting key terms from text and generating summaries = key phrase extraction and summarization = NLP workloads.

---

## Q94 *(Hotspot)*
Which NLP task is most appropriate for an email service that needs to automatically sort incoming emails into categories?

**✅ Classify email messages** (document categorization / text classification)
NLP includes document categorization, which can classify emails into categories like spam/not spam or support topic areas.

---

## Q95
Which AI service can you use to interpret the meaning of a user input such as "Call me back later"?

- A. Translator
- B. Text Analytics
- C. Speech
- D. Language Understanding (LUIS)

**✅ D**
LUIS is designed to predict the intent behind natural language input (utterances). Text Analytics performs sentiment and key phrase extraction; Translator handles language translation; Speech handles audio.

---

## Q96
You are developing a chatbot. Which service should you use to determine a user's intent?

- A. Translator
- B. QnA Maker
- C. Speech
- D. Language Understanding (LUIS)

**✅ D**
LUIS classifies user text into predefined intents (e.g., "BookFlight," "CancelOrder"). QnA Maker finds answers to questions from a knowledge base but does not classify intents.

---

## Q97
You need to make your company's press releases available in multiple languages. Which service should you use?

- A. Translator
- B. Text Analytics
- C. Speech
- D. Language Understanding (LUIS)

**✅ A**
Azure Translator is a cloud-based machine translation service that converts text between languages in near real time.

---

## Q98 *(Hotspot — Yes/No)*
Text Analytics can detect the language a document is written in → Yes/No? | Text Analytics can identify a handwritten signature in an image → Yes/No? | Text Analytics can recognize named entities like people, places, and organizations → Yes/No?

**✅ Yes / No / Yes**
- Language detection = Text Analytics feature ✅
- Handwritten signature identification = computer vision / ink recognition, not Text Analytics ❌
- Named entity recognition (NER) = Text Analytics feature ✅

---

## Q99 *(Drag and Drop — NLP Workloads)*
Match: "extract people, places, and organizations from articles" / "determine if product reviews are positive or negative" / "convert text from English to French"

**✅ Entity recognition / Sentiment analysis / Translation**

---

## Q100 *(Hotspot — Yes/No)*
Content Moderator can detect offensive or profane text → Yes/No? | Computer Vision can detect offensive content in text → Yes/No? | Text Analytics can determine whether customer feedback is positive or negative → Yes/No?

**✅ Yes / No / Yes**
- Content Moderator detects profanity and offensive text ✅
- Computer Vision analyzes images, not text content ❌
- Text Analytics sentiment analysis determines positive/negative/neutral tone ✅

---

## Q101
You are analyzing customer reviews to determine how positive or negative each one is. Which NLP workload is this?

- A. language detection
- B. sentiment analysis
- C. key phrase extraction
- D. entity recognition

**✅ B**
Classifying text as positive, negative, or neutral = sentiment analysis.

---

## Q102
You process text through an NLP API and receive output showing labeled entities like [DateTime], [PersonType], [Skill], and [Location]. Which NLP task was performed?

- A. entity recognition
- B. key phrase extraction
- C. sentiment analysis
- D. translation

**✅ A**
Named Entity Recognition (NER) identifies and categorizes entities in text — people, places, organizations, dates, quantities, etc. The square brackets with category tags are the signature output of NER.

---

## Q103 *(Drag and Drop — Text Analytics Features)*
Match: "determine if a support ticket is frustrated or satisfied" / "identify the key concepts and topics mentioned in a ticket" / "identify if the ticket mentions a specific product name, date, or location"

**✅ Sentiment analysis / Key phrase extraction / Entity recognition**

---

## Q104
A user asks: "Which act is playing on the main stage?" in a LUIS-powered music festival app. This question is an example of which LUIS element?

- A. an intent
- B. an utterance
- C. a domain
- D. an entity

**✅ B**
An utterance is the actual text input from a user. An intent is what the user wants to accomplish (e.g., "FindSchedule"). An entity is a specific piece of data extracted from the utterance (e.g., "main stage").

---

## Q105
You built a QnA Maker bot from an FAQ page. You want to add professional greetings and conversational responses. What should you do?

- A. Increase the confidence threshold
- B. Enable active learning
- C. Create multi-turn questions
- D. Add chit-chat

**✅ D**
Chit-chat in QnA Maker adds a set of predefined conversational responses (greetings, thanks, farewells) to make the bot feel more natural and friendly.

---

## Q106
You need to develop a chatbot using a Word document troubleshooting guide and an FAQ webpage as its knowledge sources. Which service should you use to process the documents?

- A. Azure Bot Service
- B. Language Understanding
- C. Text Analytics
- D. QnA Maker

**✅ D**
QnA Maker ingests documents (PDF, DOC, web pages) and creates a searchable knowledge base of question-answer pairs that a bot can use to respond to user queries.

---

## Q107
You are building a LUIS model for e-commerce. You need to ensure the model detects utterances that fall outside its intended scope. What should you do?

- A. Test the model using new utterances
- B. Add utterances to the None intent
- C. Create a prebuilt task entity
- D. Create a new model

**✅ B**
The None intent captures utterances that don't match any defined intent. Populating it with out-of-scope examples trains the model to recognize and handle inputs it's not designed for.

---

## Q108
You have a QnA Maker chatbot and want it to improve its response relevance over time based on user feedback. What should you use?

- A. key phrase extraction
- B. sentiment analysis
- C. business logic
- D. active learning

**✅ D**
Active learning in QnA Maker collects user feedback on bot responses and uses it to suggest improvements to the knowledge base, making the bot smarter over time.

---

## Q109
You are developing a conversational AI solution that communicates through email, Microsoft Teams, and webchat. Which service should you use?

- A. Text Analytics
- B. Azure Bot Service
- C. Translator
- D. Form Recognizer

**✅ B**
Azure Bot Service connects a bot to multiple channels (email, Teams, webchat, Slack, etc.) through a single integration layer. It is the service that enables multi-channel conversational AI deployment.

---

## Q110 *(Hotspot — Yes/No)*
A chatbot can be used to answer customer questions → Yes/No? | A chatbot can use machine learning to learn from new information in real time without retraining → Yes/No? | A standard web form with dropdown menus is an example of a conversational AI workload → Yes/No?

**✅ Yes / No / No**
- Chatbots answering questions = core use case ✅
- Real-time unsupervised self-learning without retraining = not standard bot behavior ❌
- A static web form is not conversational AI; it requires no natural language understanding ❌

---

## Q111
What are three ways to create question-and-answer content in QnA Maker?

- A. Generate Q&As from an existing webpage
- B. Use AutoML to train a model based on questions
- C. Manually enter questions and answers
- D. Connect to Cortana and ask questions
- E. Import chit-chat content from a predefined data source

**✅ A, C, E**
QnA Maker supports: (A) extracting Q&A from existing web pages or documents, (C) manual entry, and (E) importing chit-chat personas. AutoML and Cortana integration are not QnA Maker creation methods.

---

## Q112
You have an FAQ PDF and need to create a conversational support system from it. Which service should you use?

- A. QnA Maker
- B. Text Analytics
- C. Computer Vision
- D. Language Understanding (LUIS)

**✅ A**
QnA Maker is specifically designed to build a conversational question-and-answer layer from existing FAQ documents, manuals, and web pages.

---

## Q113
You need to reduce the load on telephone operators using a chatbot that answers simple predefined questions. Which two services should you use?

- A. Text Analytics
- B. QnA Maker
- C. Azure Bot Service
- D. Translator

**✅ B, C**
QnA Maker provides the knowledge base of answers; Azure Bot Service provides the conversational interface and channel integration to deliver those answers to users.

---

## Q114
Which two scenarios are examples of a conversational AI workload?

- A. a smart home device that responds to "What will the weather be today?"
- B. a website using a knowledge base to interactively answer user questions
- C. assembly line machinery that inserts headlamps into cars
- D. monitoring machinery temperature to trigger a fan

**✅ A, B**
Both involve natural language interaction between a user and an AI. Options C and D are automated physical/sensor systems with no conversational component.

---

## Q115
A diagram shows: User → Website → Bot → Knowledge Base → Response. Which AI solution is shown?

- A. sentiment analysis
- B. a chatbot
- C. a machine learning model
- D. a computer vision application

**✅ B**
The flow of user input → bot → knowledge base → answer is the classic architecture of a chatbot (conversational AI) using QnA Maker and Azure Bot Service.

---

## Q116
You need a web-based AI solution for customer support that guides users to the best resource or answer. Which service should you use?

- A. Custom Vision
- B. QnA Maker
- C. Translator Text
- D. Face

**✅ B**
QnA Maker creates a conversational question-answering system from existing content, guiding users to the best answer from the knowledge base.

---

## Q117
Which AI service should you use to create a bot from an FAQ document?

- A. QnA Maker
- B. Language Understanding (LUIS)
- C. Text Analytics
- D. Speech

**✅ A**
QnA Maker is purpose-built to extract question-and-answer pairs from FAQ documents and power a bot with them.

---

## Q118 *(Hotspot)*
Which type of AI solution enables users to interact with software through natural language via channels like websites, apps, Teams, and Skype?

**✅ Conversational AI**
Conversational AI (chatbots and virtual agents) enables natural language interaction across multiple communication channels.

---

## Q119
Which scenario is an example of a webchat bot?

- A. Determine whether concert reviews are positive or negative
- B. Translate customer questions from a kiosk into English
- C. Route emails to the correct person based on content
- D. Answer common questions about scheduled events and ticket purchases from a website interface

**✅ D**
A webchat bot provides interactive, natural language Q&A through a website interface. Option D describes exactly that. The others describe NLP analysis tasks, translation, and email routing — not conversational chat.

---

## Q120 *(Hotspot — Yes/No)*
QnA Maker is used to determine the intent of a user's utterance → Yes/No? | QnA Maker is used to find the best answer from a knowledge base for a user's query → Yes/No? | LUIS is used to find the answer to a user's question → Yes/No?

**✅ No / Yes / No**
- LUIS determines intent; QnA Maker finds answers — they serve different purposes
- QnA Maker's core function is returning the best matching answer from a knowledge base ✅
- LUIS classifies intent; it does not return answers ❌

---

## Q121 *(Hotspot — Yes/No)*
Azure Bot Service can be connected to Facebook Messenger → Yes/No? | Azure Bot Service can be connected to Microsoft Teams → Yes/No? | Azure Bot Service can be connected to Office 365 email → Yes/No?

**✅ Yes / Yes / Yes**
Azure Bot Service supports a wide range of channels including Facebook Messenger, Microsoft Teams, Office 365 email, Slack, Kik, LINE, Telegram, WeChat, and more.

---

## Q122 *(Hotspot — Yes/No)*
An Azure bot can use LUIS to understand user intent → Yes/No? | An Azure bot can respond to users in natural language → Yes/No? | An Azure bot can automatically connect to and extract data from any external website → Yes/No?

**✅ Yes / Yes / No**
- Bots can integrate with LUIS for intent classification ✅
- Bots respond in natural language ✅
- Bots cannot automatically connect to arbitrary external websites without explicit configuration ❌

---

## Q123
Which two scenarios are examples of conversational AI workloads?

- A. a telephone answering service with a pre-recorded message
- B. a chatbot that lets users find answers on a website by themselves
- C. telephone voice menus to reduce load on human staff
- D. a service that creates FAQ documents by crawling public websites

**✅ B, C**
Both B and C involve interactive, dynamic conversation between a user and an AI system. A pre-recorded message (A) is one-way; website crawling (D) is data processing, not conversation.

---

## Q124 *(Hotspot — Yes/No)*
Azure Bot Service can integrate with Azure Cognitive Services → Yes/No? | Azure Bot Service enables conversational interaction with users → Yes/No? | QnA Maker creates question-and-answer sets automatically without a knowledge base → Yes/No?

**✅ Yes / Yes / No**
- Bot Service integrates with Cognitive Services (LUIS, QnA Maker, Speech, etc.) ✅
- Bot Service enables conversational AI interactions ✅
- QnA Maker requires a knowledge base (seeded from documents or manual entry) to generate Q&A pairs — it does not create them from nothing ❌

---

## Q125 *(Hotspot — Yes/No)*
Azure Bot Service can use a QnA Maker knowledge base to answer user questions → Yes/No? | Azure Bot Service uses the Speech service to support voice interaction → Yes/No? | Azure Bot Service can be embedded directly into a web page → Yes/No?

**✅ Yes / No / Yes**
- Bot + QnA Maker integration is a standard architecture ✅
- Bot Service itself does not include speech; a separate Speech service integration is required ❌
- Bot Service supports a Web Chat channel that can be embedded in web pages ✅

---

## Quick Reference — Responsible AI Principles

| Principle | Key Idea | Trigger Words |
|---|---|---|
| **Fairness** | No bias by gender, race, religion | bias, discriminate, hiring tool, equal performance |
| **Reliability & Safety** | Consistent, safe, resilient | unexpected conditions, resilience, edge cases, override |
| **Privacy & Security** | Protect personal data | data protection, personal info, GDPR |
| **Inclusiveness** | Benefits everyone incl. disabled | accessibility, disabilities, barriers, unintentionally exclude |
| **Transparency** | Understandable and explainable | explainable, black box, audit, documentation, factors |
| **Accountability** | Humans responsible for AI | humans override, responsible for, governance, regulators |

---

## Quick Reference — ML Task Selection

| Scenario Clue | ML Type |
|---|---|
| Predict a **number** (price, temperature, sales) | **Regression** |
| Predict **yes/no** or a category | **Classification** |
| **Group** data by similarity (no predefined labels) | **Clustering** |
| Detect **unusual patterns or outliers** | **Anomaly Detection** |
| Predict **two outcomes only** | **Binary Classification** |
| Predict **3+ categories** | **Multiclass Classification** |

---

## Quick Reference — Azure AI Services

| Need | Service |
|---|---|
| Extract text from images/scans | Azure AI Vision OCR |
| Train custom image model | Custom Vision |
| Detect/identify faces | Azure AI Face API |
| Extract fields from invoices/receipts/forms | Azure AI Document Intelligence (Form Recognizer) |
| Sentiment, NER, key phrases, language detection | Azure AI Language (Text Analytics) |
| Speech-to-text / Text-to-speech | Azure AI Speech |
| Translate between languages | Azure Translator |
| Understand user intent in conversation | LUIS |
| Build Q&A from documents | QnA Maker |
| Multi-channel bot deployment | Azure Bot Service |
