# 9. Data Requirements

## Data Elements

| Data Element | Source | Format | Required |
|---|---|---|---|
| Patient ID | SMART EHR | Numeric | Yes |
| Patient Name | SMART EHR | Text | Yes |
| Patient Age | SMART EHR | Numeric | Yes |
| Patient Gender | SMART EHR | Text | Yes |
| Facility Name | SMART EHR | Text | Yes |
| Admission Date | SMART EHR | Date | Yes |
| Last Admitted Date | SMART EHR | Date | Yes |
| Relapse Risk Level | MyndWell AI | Text (High/Medium/Low) | Yes |
| Relapse Risk Percentage | MyndWell AI | Numeric (%) | Yes |
| Prediction Date | MyndWell AI | Date | Yes |
| Current Dosage | SMART EHR | Text | Yes |
| Medication Name | SMART EHR | Text | Yes |
| AI Feedback | MyndWell User | Boolean (thumbs up/down) | No |

## Data Mapping

| Source System | Target System | Data Element | Transformation |
|---|---|---|---|
| SMART EHR | MyndWell | Patient Demographics | HL7 ADT message |
| SMART EHR | MyndWell | Admission Data | HL7 ADT message |
| Methasoft | MyndWell | Medication Data | MuleSoft API |
| MyndWell | SMART EHR | Risk Level | MuleSoft API |

## Data Quality Rules

- Patient ID must be unique per facility
- Admission date must be within the last 180 days for prediction display
- Risk level must be one of: High, Medium, Low
- Risk percentage must be between 0 and 100
- Dosage must match the current active prescription
