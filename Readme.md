# Prerequisites
Install Python3, Pip,anaconda, Jupyter, Vscode , Python & Jupyter extension for vscode

# Create virtual env
```
python3 -m venv ./venv  
source ./venv/bin/activate
ipython kernel install --user --name=venv
```
# To run on browser

```
jupyter-notebook
```

# Create file with ext .ipynb (notebook) or .py based on usecase


# Dependencies mgmt
```
pip3 freeze > requirements.txt
pip3 install -r requirements.txt
pip3 install <pakage name>
pip3 uninstall <pakage name>
```