# VendorFlow – PS-2 Case Study

This directory contains the VendorFlow vendor onboarding demonstration application.

To run locally:

```bash
pip install -r requirements.txt
streamlit run app.py
```

To deploy publicly, use Streamlit Community Cloud and select this `app.py` entry point. The included local SQLite demo data is not part of this source listing; the app initializes a fresh synthetic demo database on first run.
