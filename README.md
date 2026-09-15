# ChainGuard AI
## L2 — Supply Chain Disruption Assistant & Fleet Utilisation Optimizer

Ready-to-run hackathon MVP demonstrating disruption tracking, shipment risk scoring,
rerouting recommendations, idle fleet identification, cold-chain alerts, and an AI assistant.

### Windows
```bat
python -m venv .venv
.venv\Scripts\activate
pip install -r src\requirements.txt
python src\seed.py
python src\app.py
```
Open http://127.0.0.1:5000

IBM Bob: a Bob adapter and local demo fallback are included. For the final submission,
connect the official IBM Bob endpoint/credentials supplied by the organizers.


## Render Deployment
Create a Render Web Service from this GitHub repository. Build command: `pip install -r src/requirements.txt`. Start command: `sh start.sh`. No database service is required; the demo seeds a local SQLite database at startup. The generated public URL is the URL to submit.
