Run via

```bash

export REGULATIONS_GOV_API_KEY="UXEzuMPVgDW6VgcVE2e4SLw5WGX4bVKPj0QCagHw"
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python scripts/fetch_roundup.py --config config.yaml
```