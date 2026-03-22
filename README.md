# Insurance Lead Conversion Prediction - ML Application

## Overview
This project predicts whether an insurance lead will convert into a customer using a machine learning classification model.

---

## Model
- Single-stage classification model
- Output:
  - 1 → Converted
  - 0 → Not Converted

---

## Quickstart (Local Setup)

### Create virtual environment
```uv venv```

### Install dependencies
```uv pip install -r requirements.txt```

---

## Project Structure

Place your trained model file inside:

```models/improved_model.pkl```

---

## Run Locally

### Streamlit UI
```uv run streamlit run app.py```

---

## Config

- Model is loaded inside `app.py`
- Ensure the path matches: ```models/improved_model.pkl```

---

## Dependency Management

To install:
```uv pip install -r requirements.txt```

To freeze:
```uv pip freeze > requirements.txt```

---

## Git Instructions

```
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/SukritiKashyap/insurance-lead-conversion-prediction.git
git push -u origin main

```

## Deployment

Deployed using Streamlit Community Cloud:

https://insurance-conversion-prediction.streamlit.app/

## Important Notes

- Feature order must match training data
- Model file (improved_model.pkl) must exist in repo
- Dependency versions must match requirements.txt

## Environment
Python 3.12 recommended

## Note
- Model is trained on synthetic dataset
- Performance is moderate (baseline model)
- Project demonstrates end-to-end ML workflow:
   - Data preprocessing
   - Feature engineering
   - Model training
   - Deployment
