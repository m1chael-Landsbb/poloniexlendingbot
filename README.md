# Coalition Engine Python/Flask

# Coalition Engine Python/Flask

Welcome to the Coalition Engine backend powered by Flask.

## Installation
```bash
git clone https://github.com/devforge/CoalitionEnginePython-Flask.git
cd CoalitionEnginePython-Flask
pip install -r requirements.txt
```

## Usage
```bash
python app.py
```

## Additional Configuration

Modify `config.py` to adjust database connections and API endpoints.

## Deployment

For production environments:
```bash
gunicorn --bind 0.0.0.0:8000 app:app
```

---

### **Configuration Steps**
1. **Open editor** with:
   ```bash
   nano config.py
   ```
