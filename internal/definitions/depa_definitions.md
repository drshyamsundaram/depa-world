# Data Ecosystem Roles and Classifications

## 1.1 Key Actors in the Data Ecosystem

### 1.1.1 Technical Standards Organization (TSO)
**Definition:**  
An actor responsible for developing, publishing, and maintaining the technical specifications, protocols, and standards that ensure interoperability, security, and compliance across the data ecosystem.

**Example:**  
The DEPA Foundation publishes and maintains the open-source protocols, codebase and API specifications that all actors in the data ecosystem must implement to ensure compliant and interoperable data exchange.

---

### 1.1.2 Self-Regulatory Organization (SRO)
**Definition:**  
An actor with authority to define, enforce, and oversee data-related regulations, ethical standards, and operational norms within a specific industry or sector.

**Example:**  
For the healthcare sector, Samyog acts as the SRO. It certifies DPI for AI (DEPA) training and inferencing use cases; along with Confidential Clean Room (CCR) Certification. It also ensures actors are DEPA compliant and facilitates dispute resolution.

---

### 1.1.3 Data Record and Data Set
**Definition:**  
A Data Record is an atomic collection of related data elements. A Data Set is a collection of Data Records that conform to the same schema.

**Example:**  
Rajni wears a health tracker that records her step count and heart rate daily. Each day's measurements form one Data Record. A month's worth of these records forms a Dataset.

---

### 1.1.4 Model
**Definition:**  
A model is a mathematical or computational construct that represents a real-world process or system, used to generate inferences, predictions, or decisions from input data.

**Example:**  
Statistical models, generative models, recommendation systems, classification algorithms, ensemble models.

---

### 1.1.5 Data Source
**Definition:**  
The origin from which a data record is generated.

**Example:**  
Rajni’s wearable device is the Data Source for her health data. Because Rajni owns the device, she is the effective owner of the data record.

---

### 1.1.6 Data Subject (DS)
**Definition:**  
The individual to whom the personal data relates or belongs.

**Example:**  
Rajni is the Data Subject for data collected from her device. If her child used the device, Rajni, as guardian, is also considered a Data Subject.

---

### 1.1.7 Data Provider (DP)
**Definition:**  
An actor that determines the purpose and means of processing personal data.

**Example:**  
GoodHealth Wearables acts as a Data Provider by defining how data from its fitness trackers is collected and used.

---

### 1.1.8 Data Consumer (DC)
**Definition:**  
An actor who derives value from data by using it for analytics, model training, or inference.

**Example:**  
HealthModels uses aggregated data to train a fitness model (Training Data Consumer). Swasthya Assurance Corp uses a trained model for premium pricing (Inferencing Data Consumer).

---

### 1.1.9 Data Collective (DX)
**Definition:**  
An actor that aggregates, validates, and curates data from multiple providers and governs access to it.

**Example:**  
HealthyLife Data Collective curates fitness data from providers like GoodHealth Wearables and provisions datasets to HealthModels.

---

### 1.1.10 Technology Service Provider (TSP)
**Definition:**  
An actor offering infrastructure or computational services enabling secure data processing without direct access to data.

**Example:**  
A2Z Computing provides a Confidential Clean Room for training models. Both A2Z and its partner, C2C Cloud Services, are TSPs certified by Samyog.

---

### 1.1.11 Discovery Agent (DA)
**Definition:**  
A service that facilitates discovery of datasets and models by exposing metadata, not actual data.

**Example:**  
AIKosh lists metadata for available fitness datasets and models. HealthModels uses it to discover datasets without accessing raw data.

---

### 1.1.12 Application Builder (AB)
**Definition:**  
An actor that integrates data-derived outputs into user-facing applications.

**Example:**  
Hridayalogic builds a fitness app using a model from HealthModels, assisted by MakerStudio Inc (a TSP).

---

### 1.1.13 Application User (AU)
**Definition:**  
An individual who uses an application, generating new data and becoming a Data Subject.

**Example:**  
Amit uses the Hridayalogic app, making him an Application User and a Data Subject.

---

### 1.1.14 AI Chain (AIC)
**Definition:**  
A cryptographic framework within DEPA that logs provenance data for datasets, models, and inferences to support traceability and compliance.

**Example:**  
Hash records of datasets, training parameters, and models used by HealthModels are logged in the AI Chain for auditability.

---

## 1.2 Categories of Data

### 1.2.1 Classification by Privacy and Accessibility

#### 1.2.1.1 Private Personal Data
**Description:**  
Data that is personal and private, requiring stringent protection.

**Example:**  
A patient’s EHR with identifying details and diagnosis.

#### 1.2.1.2 Public Personal Data
**Description:**  
Personal data made public by consent or breach.

**Example:**  
A public list of marathon finishers with names and times.

#### 1.2.1.3 Private Non-Personal Data
**Description:**  
Confidential information not tied to individuals.

**Example:**  
A company’s internal financial report or secret recipe.

#### 1.2.1.4 Public Non-Personal Data
**Description:**  
Openly accessible data without personal identifiers.

**Example:**  
Government-published weather reports or census data.

#### 1.2.1.5 Private Personal Aggregate Data
**Description:**  
Statistical data from personal records, kept confidential.

**Example:**  
An internal hospital report on patient recovery metrics.

#### 1.2.1.6 Public Personal Aggregate Data
**Description:**  
Published statistics derived from personal records.

**Example:**  
Health prevalence studies released to the public.

#### 1.2.1.7 Private Non-Personal Aggregate Data
**Description:**  
Summarized non-personal data kept private.

**Example:**  
A market research report sold to a client.

#### 1.2.1.8 Public Non-Personal Aggregate Data
**Description:**  
Openly published summaries of non-personal data.

**Example:**  
Stock exchange reports showing average trading volumes.

#### 1.2.1.9 Open Data
**Description:**  
Freely usable data under open licenses.

**Example:**  
WHO Global Health Observatory data or OpenStreetMap.

#### 1.2.1.10 Closed Data
**Description:**  
Data with restricted access or licensing.

**Example:**  
Gartner market reports or internal company databases.

---

### 1.2.2 Classification by Origin and Quality

#### 1.2.2.1 Natural Data
**Description:**  
Data directly measured from real-world sources.

**Example:**  
Sensor readings, GPS logs, or user clickstreams.

#### 1.2.2.2 Synthetic Data
**Description:**  
Computationally generated data mimicking real data.

**Example:**  
Simulated transaction data for testing or training.

#### 1.2.2.3 Noisy Data
**Description:**  
Contains random or irrelevant data artifacts.

**Example:**  
Distorted images or recordings with static.

#### 1.2.2.4 Clean Data
**Description:**  
Accurate and standardized data.

**Example:**  
Validated customer address lists.

#### 1.2.2.5 Verified Data
**Description:**  
Data authenticated against a trusted source.

**Example:**  
Cleared transactions by a financial institution.

#### 1.2.2.6 Falsified Data
**Description:**  
Tampered or fraudulent data.

**Example:**  
Fake research results or insurance fraud.

---

### 1.2.3 Classification by Relational and Structural Properties

#### 1.2.3.1 Linked Data
**Description:**  
Data connected with relational references to other data sets.

**Example:**  
Product and reviews linked via shared product ID.

#### 1.2.3.2 Orphaned Data
**Description:**  
Isolated datasets lacking integration.

**Example:**  
Legacy data without documentation or relational keys.

#### 1.2.3.3 Rich Data
**Description:**  
High-dimensional and metadata-rich data.

**Example:**  
3D medical imaging with layered metadata.

#### 1.2.3.4 Sparse Data
**Description:**  
Datasets with many empty or null fields.

**Example:**  
Sparse user-item rating matrix.

---

### 1.2.4 Classification by Temporal State

#### 1.2.4.1 Data at Rest
**Description:**  
Stored data, not actively moving.

**Example:**  
Archived records or saved files.

#### 1.2.4.2 Data in Transit
**Description:**  
Data currently being transferred.

**Example:**  
Live-streaming or network data packets.

#### 1.2.4.3 Short-Lived Data
**Description:**  
Ephemeral data relevant for a short time.

**Example:**  
An OTP or temporary session ID.

#### 1.2.4.4 Long-Lived Data
**Description:**  
Data needed for long-term reference.

**Example:**  
Census archives or contract documents.

---

### 1.2.5 Classification by Jurisdictional Scope

#### 1.2.5.1 Territorial Data
**Description:**  
Data kept within one legal jurisdiction.

**Example:**  
German health records under EU data protection.

#### 1.2.5.2 Cross-Border Data
**Description:**  
Data accessed or processed across jurisdictions.

**Example:**  
Customer data stored outside its country of origin.

---
