# AI-in-Healthcare

This repository contains resources for the AI in Healthcare class for aSSIST students. It includes lecture materials, synthetic patient data and prompt examples for healthcare AI applications.

## Repository Structure

### `data/` Directory

#### `synthea_sample_data_fhir_dstu2_latest/`
Contains synthetic patient records generated using Synthea, a synthetic patient data generator. These records are in FHIR (Fast Healthcare Interoperability Resources) DSTU2 format.

**Features:**
- FHIR DSTU2 compliant JSON format
- Realistic patient demographics and medical history
- Diverse patient profiles with various medical conditions
- Each record includes patient information, encounters, conditions, medications, and procedures
- Useful for testing healthcare AI models and applications

**Sample Files:**
- Patient records with unique identifiers (e.g., `Adela471_Danica886_Schmitt836_0c1a1859-29c7-4f11-f21c-20a7099e8613.json`)
- Each file contains a complete patient bundle with comprehensive medical data

#### `synthetic_patients/`
Additional synthetic patient data for educational and testing purposes.

### `prompt_examples/` Directory

Contains example prompts demonstrating various healthcare AI use cases:

- **`diagnosis_assistant.md`** - Prompts for AI-assisted diagnosis support
- **`medical_education.md`** - Educational prompts for learning healthcare concepts
- **`patient_communication.md`** - Examples for patient-facing AI interactions
- **`treatment_planning.md`** - Prompts for treatment planning assistance
- **`README.md`** - Documentation for the prompt examples

## Data Format

The synthetic patient data follows the FHIR DSTU2 standard, which includes:
- Patient demographics
- Medical conditions
- Medications
- Procedures and encounters
- Allergies and immunizations
- Observations and vital signs

## Usage

These resources are designed for:
- Educational demonstrations of healthcare informatics
