# Part Manager

> Python/Tkinter desktop GUI app to manage customer computer parts. This app uses Sqlite3 to store data

## Usage

```bash
# Install package
pip install -r requirements.txt

# Run script
python part_manager.py


# Compiled with Pyinstaller

# Windows
pyinstaller --onefile --windowed part_manager.py

# MacOS
pyinstaller --onefile --add-binary='/System/Library/Frameworks/Tk.framework/Tk':'tk' --add-binary='/System/Library/Frameworks/Tcl.framework/Tcl':'tcl' part_manager.py
```