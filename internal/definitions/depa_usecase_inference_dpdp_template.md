# DEPA Inferencing - Use Case Template

---

## Use Case - Partnership Structure

| Usecase   | ABC Travel & AlphaBank Credit Card Partnership | ABC Travel & AlphaBank Credit Card Partnership | ABC Travel & AlphaBank Credit Card Partnership |
|-----------|-----------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| Type      | INDIA                                         | DPDP Regulation                               | AI Inferencing (Secure)                       |
| Usecase ID| DEPA_SAMPLE_FINANCE_INDIA_DPDP_INFERENCE_001  | DEPA_SAMPLE_FINANCE_INDIA_DPDP_INFERENCE_001  | DEPA_SAMPLE_FINANCE_INDIA_DPDP_INFERENCE_001  |

### Overview
AlphaBank, a trusted financial institution (headquartered in Coimbatore, India), is a large bank with multiple branches all over India. They have a diverse range of financial services offerings including credit cards. They also have a strong digital presence with both app and web capabilities, including strong technical capabilities with API-led integrations.

This use case illustrates the approach using the India-specific DPDP regulation.

This case study explores the strategic partnership between ABC Travel, a leading digital travel app, and AlphaBank, a trusted financial institution. Together, they launched a co-branded credit card offer, leveraging an ecosystem of service providers to deliver a seamless and rewarding user experience.

#### Partnership Objective

The primary goal was to drive user engagement for ABC Travel and boost credit card issuance for AlphaBank by providing tailor-made travel rewards and frictionless access to premium financial services through the ABC Travel app and web.

#### Initial Steps
ABC Travel and AlphaBank visit the Samyog website to get clarity on the needful process. Post this, they reach out for support on their use case.

Samyog provides a comprehensive engagement mechanism to all stakeholders—technical, business, and legal/compliance—on the use case and its implementation approach.

Samyog provides a detailed approach and technical reference document that allows ABC Travel and AlphaBank to review the technical details (Samyog and DEPA World).

Detailed working steps are initiated by ABC Travel and AlphaBank.

---

## Key Stakeholders & Market Players

| DEPA Definition | DPDP Role      | Entity Name     | Description                                                                                                                                                                                                                                   |
|-----------------|---------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data Provider   | Data Fiduciary | AlphaBank       | HQ based in Coimbatore, India. Owns bank user data, ensures data protection and regulatory adherence.                                                                                                   |
| Data Provider   | Data Fiduciary | ABC Travel      | HQ based in Indore, India. Owns travel user data, ensures data protection and regulatory adherence.                                                                                                     |
| TSO             | TSO           | DEPA Foundation | Provides technical specifications and framework for AI, including training and inferencing. Reference implementation and codebase are available through depa.world.                                      |
| SRO             | SRO           | Samyog          | India AI SRO for AI-related use cases, especially AI Training and Inference. Provides guidance, specifications, and AI market ecosystem related services.                                               |
| TSP             | TSP           | Bank Tech       | TSP for AlphaBank, registered with the SRO (Samyog): manages app & web development (UI, integrations, backend), technical infrastructure, DEPA inferencing compliance, offers, and model maintenance.   |
| TSP             | TSP           | ABC Tech        | TSP for ABC Travel, registered with SRO (Samyog): manages app & web development, technical infrastructure, core integrations like API integration with AlphaBank Credit Card Offer API.                  |
| TSP             | CSP           | DEF Cloud Tech  | India-based Cloud Service Provider (CSP), registered with SRO (Samyog): ABC Travel's capabilities are hosted in its private clouds; offers DEPA-compliant Confidential Clean Room (CCR) infrastructure. |
| TSP             | CCR Provider  | DEF Cloud Tech  | Provides CCR services for secure inferencing, used by both ABC Travel and AlphaBank in their private clouds. The DEPA-compliant inference use case is hosted in a separate instance.                    |

---

# Solution Architecture
## Seamless Co-branded Credit Card Integration: ABC Travel & AlphaBank

### Seamless Application Experience

1. **User Login & Trip Planning**
   - The user logs in to the ABC Travel App.
   - After planning a trip and reaching checkout, the user is presented with a banner promoting the AlphaBank co-branded credit card.
   - The banner includes relevant Terms & Conditions.

2. **Embedded Credit Card Offer**
   - The ABC Travel App leverages AlphaBank's DEPA Inference compliant Credit Card Offer Secure APIs.
   - Key customer data (handled securely) is passed to the AlphaBank API to enable offer eligibility checking.

3. **Secure Offer Delivery**
   - AlphaBank’s Secure API processes the request.
   - If approved, the API returns a secure offer URL to the user.

4. **Consent & Card Application**
   - Interested users are redirected for consent on the AlphaBank platform.
   - AlphaBank completes further verification and processes the application.

---

### Integrated KYC and Instant Issuance

- AlphaBank performs real-time offer checking using advanced inferencing, with user consent.
- Upon successful processing, the credit card offer is extended immediately to the user.
- KYC (Know Your Customer) checks and instant card issuance are integrated into the digital journey.

---

### Personalized Rewards & In-App Integration

- **Enhanced Rewards:** Cardholders get additional reward points for bookings via ABC Travel using the co-branded card.
- **Personalized Offers:** Users receive tailored, real-time travel offers and enhanced rewards within the app.
- **Exclusive Benefits:** Enjoy extra perks such as lounge access, travel insurance, and priority customer support.

---

### Compliance & Data Security

- **DEPA Framework:** The end-to-end solution adheres to the DEPA (Data Empowerment and Protection Architecture) framework principles.
- **Regulatory Oversight:** AlphaBank and ABC Travel, in partnership with India SRO (Samyog), ensure compliance with India DPDP (Digital Personal Data Protection) regulations.
- **Ecosystem Support:** All ecosystem partners commit to and support the DEPA framework, ensuring secure, privacy-focused collaboration.

---
# Market Impact
## Impact Highlights: ABC Travel & AlphaBank Integration

### User Growth
- **Increased Engagement:**  
  ABC Travel experienced a significant rise in app engagement and booking frequency after the launch.

### New Credit Card Customers
- **High Activations:**  
  AlphaBank saw above-average credit card activations, notably among millennial and digital-first users.

### Ecosystem Efficiency
- **Modular Service Delivery:**  
  ABC Tech and Bank Tech's modular approach enabled rapid deployment and scalability for future campaigns.

### Compliance and Trust
- **Regulatory Confidence:**  
  Samyog’s oversight and AlphaBank’s commitment to data fiduciary responsibilities strengthened user trust and assurance of regulatory compliance.

---
# Key Takeaways

- **Privacy-First Collaboration:**  
  Leveraging DEPA, trusted market players and modular service providers can empower travel apps and banks to co-create highly personalized financial products while keeping user privacy as a core principle.

- **DEPA Inference Capability:**  
  This use case demonstrates how DEPA’s inference mechanisms enable safe personalization. Without DEPA, sharing user data between a travel company and a bank—or unauthorized use of user data by a bank—would constitute a privacy violation.

- **Scalable & Secure Technology Stack:**  
  The adoption of the right technology stack (including TSP, CSP, and CCR) ensures that the DEPA Framework delivers a scalable, rapid, and secure user experience.

- **Data Fiduciary & Compliance:**  
  Data fiduciary and compliance roles are essential for building long-term user trust in such partnerships. This commitment is further strengthened through the adoption and oversight of the Self Regulated Organisation (SRO).

---
# Conclusion

This collaboration between ABC Travel and AlphaBank, supported by Samyog (SRO) and DEPA ecosystem market participants, demonstrates how strategic partnerships, advanced AI capabilities, strong data stewardship, and seamless integration can unlock significant value across the banking and travel sectors.

---
# Annexure

## Quick Points

- **Secure & Privacy-Preserving Approach:**  
  This use case emphasizes a secure and privacy-first methodology.

- **User Contract:**  
  ABC Travel enters into a contract with the user (data principal), who interacts with the ABC Travel App.

- **Consent Management (ABC Travel):**  
  The end user provides consent via an ABC Travel consent manager, ensuring ABC Travel's compliance with DPDP regulations.

- **Consent Management (AlphaBank):**  
  For processing credit card checks, AlphaBank obtains consent through its own consent manager, ensuring AlphaBank's compliance with DPDP standards.

---

## Regulatory & Registration Processes

### Data Fiduciary Registration Flows

| Process                                                                                           | Example                               |
|---------------------------------------------------------------------------------------------------|---------------------------------------|
| — Data Fiduciary Registration Process with SRO                                                    | SRO: Samyog DF: AlphaBank             |
| — Data Fiduciary Registration Process with SRO                                                    | SRO: Samyog DF: ABC Travel            |
| —— Data Fiduciary Self-certify and subject to SRO/Regulatory audits (regulated minimum frequency) | SRO: Samyog DF: AlphaBank, ABC Travel |

### TSP, CSP, CCRP Registration Flows

| Process                                                                                | Example                                                                                             |
|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| — TSP Registration Process with SRO                                                    | SRO: Samyog TSP: ABC Tech, Bank Tech                                                                |
| — CSP, CCRP Registration with SRO                                                      | SRO: Samyog CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech                                       |
| —— TSP Certification Specification provided TSO/SRO                                     | SRO: Samyog TSP: ABC Tech, Bank Tech TSO: DEPA Foundation                                           |
| —— CSP, CCRP Certification Specification provided TSO/SRO                               | SRO: Samyog CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech TSO: DEPA Foundation                  |
| —— TSP Self-certify and subject to SRO/Regulatory audits (regulated minimum frequency) | SRO: Samyog TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech             |

---

## Scenario Identification & Contract Signing

| Process                                             | Example                                                                                                                                                                           |
|-----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| — Scenario Identification                           | SRO: Samyog SRO: Samyog DF: AlphaBank, ABC Travel TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech (Secure Inference Scenario)                        |
| —— Contract template identified                     | SRO: Samyog SRO: Samyog DF: AlphaBank, ABC Travel TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech (Contract: Secure Inference Scenario)              |
| —— Multiparty Contract Signed & Registered with SRO | SRO: Samyog SRO: Samyog DF: AlphaBank, ABC Travel TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech (Contract: Secure Inference Scenario)              |

*Note: All examples are fictional.*

---

## Scenario Execution & Go Live

| Process                                                                                                                                                                                                 | Example                                                                                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| — Execution Requirements (SRO Executed and Registered Contracts)                                                                                                 | SRO: Samyog SRO: Samyog DF: AlphaBank, ABC Travel TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech (Contract: Secure Inference Scenario)                 |
| —— Workflow Setup —— Workflow Execution ——— Infrastructure Setup ——— Data Sources ———— Data Sets ——— Compute Setup ———— CCR Setup ———— Model Setup (BYOB, BRE) ——— Service Setup ———— Buyer Service ———— Data Enrichment Integrations ——— Service Pipelines ———— Data ETL | SRO: Samyog SRO: Samyog DF: AlphaBank, ABC Travel TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech  TSO: DEPA Foundation (DEPA Secure Inference Scenario) |
| Scenario Go Live                                                                                                                                                                                        | SRO: Samyog SRO: Samyog DF: AlphaBank, ABC Travel TSP: ABC Tech, Bank Tech  CSP: DEF Cloud Tech  CCR Provider: DEF Cloud Tech (Contract: Secure Inference Scenario)                 |

