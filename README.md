
## Windows 11 Quick Start (PowerShell)

This project is a **static website**, not a Python package. There is no `pip install`, `requirements.txt`, `venv`, or Node build step. Install [Git](https://git-scm.com/downloads/win) and Python 3 if missing, then open PowerShell. Run **each command individually** in the folder where you want the project downloaded:

```powershell
git --version
```

```powershell
python --version
```

```powershell
git clone https://github.com/Tyler-Keesee/Typing-Speed-Test.git
```

```powershell
Set-Location .\Typing-Speed-Test
```

```powershell
python -m http.server 8000
```

With the server running, open **http://localhost:8000/** in Edge or Chrome. Press **Ctrl+C** in PowerShell to stop it.

**What to expect / caveats:** Serve with http.server because the page loads JavaScript as ES modules. No pip packages or venv are required.

**Verification:** The HTTP server starting proves only that files are served; it does not prove every browser feature or third-party API is functioning. Open browser Developer Tools (F12) and check Console and Network for failures.

---

# Typing-Speed-Test