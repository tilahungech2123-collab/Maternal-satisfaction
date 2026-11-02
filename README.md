# Maternal Satisfaction

Streamlit app for exploring maternal delivery-care satisfaction and predicting
satisfaction from patient and facility characteristics.

## Run locally

```powershell
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## Deploy on Streamlit Community Cloud

1. Select this repository, the `main` branch, and `app.py` as the entry point.
2. The app requires no secrets or external data connection.

The raw SPSS dataset and individual test labels/predictions are intentionally not
included in this repository. Prediction uses the included model artifacts, and
the confusion matrix is shown as aggregate counts. Raw-data previews and
descriptive charts are unavailable without a separately provided dataset.
