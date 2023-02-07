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
[Install-Dependencies]
- python3 -m pip install -r requirements.txt

Running the Web Server
[Default-Command]
- python3 manage.py runserver 
[Run-Specific-Port]
- python3 manage.py runserver <port-number>
[Run-Specific-IP]
- python3 manage.py runserver <IP:port-number>