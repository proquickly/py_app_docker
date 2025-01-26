# Home

## Setup 
1. fork this repo to your account and then clone to local.
2. make sure your entry point to your application is always app.py
3. use poetry add to add dependencies not pip
4. in pyproject.toml replace ```name = "py-app-docker"``` with your project name.
Do same in main.tf
5. replace author with yours
6. use the poetry src conventions - py files in src/package, tests in tests.
7. set host_path  to correct value in main.tf - must be full path


Build with:
```
terraform init
terraform plan
terraform apply
```
inside terraform directory.

https://github.com/proquickly/py_app_docker
