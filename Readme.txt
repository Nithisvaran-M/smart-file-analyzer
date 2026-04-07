# 🔍 Smart File Analyzer

**Professional CTF file analysis tool with auto flag detection**

## 🚀 Quick Start

### Windows Users (One Click)
1. Download this repository as ZIP
2. Extract the folder
3. Double-click `START.bat`
4. Browser opens automatically!

### Manual Run
```bash
# Install dependencies
cd backend
pip install -r requirements.txt

# Start backend
python -m uvicorn main:app --reload --port 8000

# In new terminal, start frontend  
cd frontend
python -m http.server 3000

# Open http://localhost:3000
