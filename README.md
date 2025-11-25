# Library Management System (Tkinter GUI)


Description: Library Management System — a simple desktop GUI app (Tkinter) that lets you add books, request multiple books (FCFS queue), and process requests. Useful as a small demo or teaching project for Python GUIs and basic queue-based scheduling.

Features
- Add books (name, author, quantity, ISBN)
- Display current library books
- Request multiple books in one request (format: ISBN:Quantity, comma-separated)
- FCFS request queue processing
- Simple Tkinter GUI and message dialogs

Model / Tech
- Python 3.7+
- Tkinter (standard library) for GUI
- queue.Queue for FCFS request handling

Files
- library_management_system.py — main application script (Tkinter GUI)
- requirements.txt — optional dependencies / packaging tools
- .gitignore — ignore virtualenvs and pycache
- LICENSE — MIT License

Usage (local)
1. Clone the repo:
   - git clone https://github.com/<your-username>/library-management-system.git
   - cd library-management-system

2. Create and activate a virtual environment (recommended):
   - python -m venv .venv
   - Linux / macOS: source .venv/bin/activate
   - Windows (PowerShell): .\.venv\Scripts\Activate.ps1

3. Install optional dependencies (if any):
   - pip install -r requirements.txt

4. Run the app:
   - python library_management_system.py

Notes
- Tkinter comes with the Python standard library on most platforms. If your Python distribution does not include Tkinter, install it separately (platform-specific).
- The app uses messagebox dialogs for status and errors, and a simple text widget to display the current books list.

License
- MIT License (see LICENSE file)

If you want, I can:
- Create the GitHub repository for you (I’ll need permission or the repository details and whether it should be public or private).
- Open a Pull Request to add tests, packaging, or convert into a pip-installable project.
