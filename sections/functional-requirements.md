# 7. Functional Requirements

## FR-1: Facility Selection

| ID | Requirement | Priority |
|---|---|---|
| FR-1.1 | The system shall allow users to select a facility from a dropdown menu | Must Have |
| FR-1.2 | The system shall automatically generate results after facility selection | Must Have |
| FR-1.3 | The system shall display all risk assessment results for the selected facility | Must Have |

## FR-2: Risk Level Filtering

| ID | Requirement | Priority |
|---|---|---|
| FR-2.1 | The system shall categorize patients into High, Medium, and Low risk levels | Must Have |
| FR-2.2 | The system shall allow users to filter results by risk level | Must Have |
| FR-2.3 | The system shall display color-coded risk indicators (red, yellow, green) | Must Have |
| FR-2.4 | The system shall display the relapse risk percentage for each patient | Must Have |

## FR-3: Search Capabilities

| ID | Requirement | Priority |
|---|---|---|
| FR-3.1 | The system shall allow search by Patient ID | Must Have |
| FR-3.2 | The system shall allow search by Patient Name | Must Have |
| FR-3.3 | The system shall allow search by Admission Date | Must Have |
| FR-3.4 | The system shall auto-generate results as the user types | Should Have |
| FR-3.5 | The system shall return results only for patients active within the last 180 days | Must Have |

## FR-4: Patient Risk Display

| ID | Requirement | Priority |
|---|---|---|
| FR-4.1 | The system shall display patient information (gender, age, patient ID, facility) | Must Have |
| FR-4.2 | The system shall display relapse risk level and percentage | Must Have |
| FR-4.3 | The system shall display prediction date | Must Have |
| FR-4.4 | The system shall display last admitted date | Must Have |
| FR-4.5 | The system shall display current dosage information | Must Have |
| FR-4.6 | The system shall display an AI feedback option (thumbs up / thumbs down) | Must Have |

## FR-5: AI Feedback Mechanism

| ID | Requirement | Priority |
|---|---|---|
| FR-5.1 | The system shall allow users to rate prediction accuracy with thumbs up or thumbs down | Must Have |
| FR-5.2 | The system shall feed user feedback into the AI model for continuous improvement | Must Have |
| FR-5.3 | The system shall store feedback with patient and prediction identifiers | Must Have |

## FR-6: EHR Integration

| ID | Requirement | Priority |
|---|---|---|
| FR-6.1 | The system shall integrate with the SMART EHR system | Must Have |
| FR-6.2 | The system shall provide real-time results for active patients | Must Have |
| FR-6.3 | The system shall exchange HL7 messages for patient demographics and admissions | Must Have |
| FR-6.4 | The system shall use MuleSoft APIs for data exchange with Methasoft | Must Have |
| FR-6.5 | The system shall validate message formats with clinical and technical stakeholders | Must Have |

## FR-7: Personalized Intervention Recommendations

| ID | Requirement | Priority |
|---|---|---|
| FR-7.1 | The system shall generate evidence-based intervention recommendations | Should Have |
| FR-7.2 | The system shall suggest optimized treatment pathways | Should Have |
| FR-7.3 | The system shall flag dosage adjustments for high-risk patients | Should Have |
| FR-7.4 | The system shall identify potential adverse drug interactions | Should Have |

## FR-8: Documentation and Training

| ID | Requirement | Priority |
|---|---|---|
| FR-8.1 | The system shall include a user manual with step-by-step instructions | Must Have |
| FR-8.2 | The system shall include FAQs and a glossary | Must Have |
| FR-8.3 | The system shall include a quick reference guide | Should Have |
| FR-8.4 | The system shall include training materials for clinical staff | Must Have |
