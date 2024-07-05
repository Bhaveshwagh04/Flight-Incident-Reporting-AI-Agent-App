# Flight-Incident-Reporting-AI-Agent-App

## How to run:

1. create an environment

```bash
conda create -n flight python==3.10 -y
```
2. Activate the environment

```bash
conda activate flight
```
3. install requirements
```bash
pip install -r requirements
```
# Create a .env file in the root directory and add your GROQ_API_KEY credentials as follows:

GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# Finally run the following command
```bash
streamlit run app.py
```