# SAP One ERP

[GitHub Repository](https://github.com/CHENNAMSETTYGURUTEJA/SAP_ONE_ERP)

## Run

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r backend\requirements.txt
python run.py
```

Requires MySQL. Configure `DB_USER`, `DB_PASSWORD`, and `DB_NAME` as needed.

## Links

- [Web App](http://127.0.0.1:8000/)
- [API Documentation](http://127.0.0.1:8000/docs)
- [Health Check](http://127.0.0.1:8000/api/health)
