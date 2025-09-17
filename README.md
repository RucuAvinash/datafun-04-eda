# Project Initialization: datafun-04-eda

**Repository Setup**
-  Created a new repository on GitHub named `datafun-04-eda`
-  Cloned the repository to my local machine
-  Added `.gitignore` to exclude unnecessary files
-  Added `requirements.txt` to manage dependencies
-  Verified the repository is set to **public**

**Notebook & Analysis**
-  Added a sample Jupyter notebook showing sales visualization over a 10-day period by category
-  Used the `pandas` library to create and manipulate the DataFrame
-  Applied `pandas` functions to generate a statistical summary of sales by category
-  
**Getting started**
1. Create and activate a Python virtual environment in the project root:

Windows PowerShell:

py -m venv .venv
.\.venv\Scripts\Activate

2. Upgrade packaging tools and install dependencies:

Windows PowerShell:

py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt --timeout 100

Usage
Open any Jupyter notebooks in this repository using VS Code or JupyterLab. Make sure to select the .venv interpreter/kernel.
Use the included scripts and notebooks as templates for your own datasets:
# Load the Iris dataset into a pandas DataFrame
# List column names
# Inspect first few rows of the DataFrame 

Load, clean, visualise, and report findings.
Dependencies
The project includes a comprehensive requirements.txt with common EDA packages such as jupyter, ipykernel, matplotlib, and seaborn. Review the file and uncomment or add packages you need.

Contributing
Add notebooks and small utilities that illustrate EDA techniques.
Keep the requirements.txt up-to-date with any new packages you add.
Open an issue or submit a pull request with improvements or fixes.