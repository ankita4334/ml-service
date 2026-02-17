# PCOS Fusion AI

A FastAPI-based machine learning system for predicting
Polycystic Ovary Syndrome (PCOS) using:

- Clinical symptom data
- Optional ultrasound images
- Multimodal probability fusion

## Tech Stack
- FastAPI
- Scikit-learn
- TensorFlow
- XGBoost
- NumPy

## Run Instructions
```bash
pip install -r requirements.txt
uvicorn app:app --reload
