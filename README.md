# GlycaPep-PD CVD Risk Calculator

Streamlit calculator for the project's eight-feature logistic regression model.
Enter measurements in the units shown in the app to obtain its predicted
probability for `Endpoint = 1`.

## Run locally

```bash
python -m pip install -r requirements.txt
streamlit run app.py
```

This deployment repository contains only the application, its frozen model
coefficients, and its dependency declaration. It does not contain patient-level
training or validation data.

The Unlikely / Likely word uses the model's 50% classification cutoff. The
output is for research use and is not an established, calibrated absolute
clinical risk estimate.
