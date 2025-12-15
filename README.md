# Data Analysis Pipeline using Agentic AI

## Overview
This project demonstrates an **Agentic AI–driven data analysis workflow** that answers structured analytical questions over a tabular dataset using autonomous reasoning steps.

The notebook uses a synthetic banking dataset to:
- Interpret user questions
- Decide the appropriate analytical steps
- Execute analysis (aggregations, groupings, comparisons)
- Return clear textual (and, where relevant, visual) answers

The focus of this project is **agentic reasoning over structured data**, not model training.

---

## Input & Output

**Input**
- `synthetic_bank_customer_data.csv`  
  A synthetic, non-PII dataset representing bank customers, including attributes such as age, gender, balance, region, and job classification.

**Output**
- Natural-language answers displayed directly in the notebook  
- Optional tables or visual summaries generated as part of the analysis

---

## How to Run (Google Colab Only)

This notebook is designed **only for Google Colab execution**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ritikade2/Data_Analysis_AgenticAI/blob/main/Data_Analysis_Pipeline_using_Agentic_AI.ipynb)

### Steps
1. Open the notebook in Colab using the link above.
2. Upload `synthetic_bank_customer_data.csv` when prompted  
   (or ensure it exists in the working directory).
3. Run all cells.
4. Ask analytical questions when prompted, for example:
   - What is the average account balance by gender, age group, and job classification?
   - Which regions have the highest concentration of specific job classifications?
   - How does customer balance vary across age segments?

---

## Files Included
- `Data_Analysis_Pipeline_using_Agentic_AI.ipynb`
  Colab-ready notebook implementing the agentic data analysis workflow.
- `README.md`  
  Project documentation and execution instructions.
  
---

## Notes
- The dataset is **synthetic** and contains **no real customer data**.
- The notebook emphasizes **agentic decision-making** over traditional static dashboards.
- This project is intended as a demonstration of how AI agents can reason over structured data to support analytical workflows.


