# Instruction Format for Domain-Adaptive Fine-Tuning
## Personalized Blood Test Report Interpretation

This document defines the standardized instruction–input–output format used to fine-tune a Large Language Model (LLM) for personalized blood test report interpretation. The goal is to enable the model to generalize across diverse blood test profiles while maintaining medical accuracy, safety, and clarity.

---

## 1. General Format

Each training sample must follow the JSON structure below:

```json
{
  "instruction": "<TASK DESCRIPTION>",
  "input": "<BLOOD TEST REPORT DATA>",
  "output": "<MEDICAL INTERPRETATION RESPONSE>"
}

