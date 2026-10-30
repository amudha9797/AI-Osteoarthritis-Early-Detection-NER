# AI-Osteoarthritis-Early-Detection-NER

AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers in North Eastern Region (NER).

## Project Overview

OA Early Detection System is an academic prototype designed to screen and analyze the risk of Osteoarthritis (OA) using patient information, questionnaire responses, and gait parameters.

## Main Features

* Patient Registration
* OA Questionnaire
* Gait Assessment
* OA Risk Assessment
* Patient Report
* Patient Search
* Patient Delete
* CSV Report Download
* Dashboard with Risk Analysis
* Gait Analysis Charts

## Technologies Used

* Python
* Streamlit
* Pandas
* SQLite
* HTML / CSS
* Browser Speech Synthesis

## Gait Parameters

The system analyzes:

* Walking Speed
* Stride Length
* Cadence
* Step Count
* Gait Variability

## Risk Assessment

The prototype considers:

* Age
* BMI
* Pain Level
* Questionnaire Score
* Gait Score

## Important Note

This is an academic/demo prototype for early screening and educational purposes. The calculated risk score and gait classification are not a medical diagnosis and should not replace evaluation by a qualified healthcare professional.

## Project Structure

```text
├── app.py
├── index.html
├── requirements.txt
├── data/
│   ├── README.md
│   ├── app_backup.py
│   ├── requirements.txt
│   └── sample_data.csv
├── model/
│   ├── __init__.py
│   ├── risk_engine.py
│   └── data/
│       └── utils/
│           ├── __init__.py
│           ├── calculations.py
│           └── database.py
└── utils/
    ├── __init__.py
    └── calculations.py
```

## Getting Started

### Prerequisites

- Python 3.10+

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/amudha9797/AI-Osteoarthritis-Early-Detection-NER.git
   cd AI-Osteoarthritis-Early-Detection-NER
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```
