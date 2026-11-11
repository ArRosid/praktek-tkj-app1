# App1 — Flask Simple

## Jalankan

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

Buka http://localhost:5000

- `/` — halaman utama
- `/health` — health check (JSON)

Env opsional: `APP_NAME` (default `App1`), `APP_VERSION`, `PORT`.
