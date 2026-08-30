## How to Build

```
git clone https://github.com/icountbackwards/Antislop.git
cd Antislop
python -m venv .venv 
.venv\Scripts\activate 
pip install -r requirements.txt
$env:GEMINI_FREE_API_KEY="YOUR_API_KEY"
python main.py
```

### Note

Get a Gemini API key from Google AI Studio, then set it as an environment variable:
```
$env:GEMINI_FREE_API_KEY="YOUR_API_KEY"
```
