# AeroSuite

Short installation guide for running the project on another machine.

## Requirements

- Python 3.9
- pip

## Install

```bash
python3.9 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
streamlit run originalaero.py
```

Then open the local URL shown in the terminal, usually:

```text
http://localhost:8501
```

## Project Files

- `originalaero.py` — main Streamlit application
- `requirements.txt` — Python dependencies
