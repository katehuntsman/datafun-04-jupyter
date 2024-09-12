# datafun-04-jupyter

## Create and Activate Project Virtual Environment
```
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r "requirements.txt"

git add .
git commit -m "insert message"
git push -u origin main
```

## How to Install and Run the Project
```
python3 -m pip install jupyterlab numpy pandas matplotlib seaborn scipy
```

## Set up Jupyter in VS Code
```
1. Install the Jupyter Extension: If not already installed, add the Jupyter extension to VS Code. This extension provides rich support for working with Jupyter notebooks.  
2. Open the Project Folder: Open your root project repository folder in VS Code. (Usually in your Documents folder.)
3. Select the Python Interpreter: From the command palette (Ctrl+Shift+P), select "Python: Select Interpreter" and choose the interpreter from your virtual environment.
```

## Create a Notebook
```
1. Create the Notebook: In the VS Code Explorer, create a new file i.e., yourname_eda.ipynb. Ensure it has a .ipynb extension.
2. Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.
3. Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).
```

## Import Dependencies
```
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import requests
import jupyterlab
import pyarrow
```
