# Hospital Transfer DSS (Secure Demo)

A secure, public Streamlit demo for a clinical transfer decision support prototype.
It analyzes synthetic medical report text (NLP) to infer severity and required specialty,
then ranks hospitals based on specialty match, capacity, load, and distance.

## Notes
- Uses **synthetic data only** (no real patient data).
- Built for feasibility demonstration and administrative review.

## Run locally
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# Mac/Linux: source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
