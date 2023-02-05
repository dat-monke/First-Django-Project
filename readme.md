Steps to activate Virtual Environment 
[Initialization]
- python3 -m venv <virtual-environment-name>
[Activation]
- source <virtual-environment-name>/bin/activate
[Package-Installation]
- python3 -m pip install <package-name>
[Exit-Virtual-Environment]
- deactivate
[List-Dependencies]
- python3 -m pip freeze > requirements.txt
[Redo-Dependencies]
- python3 -m pip install -r requirements.txt