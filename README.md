# sandbox-package-python
ナウでヤングなPython Packageの書き方


## Install 
```sh
git clone https://github.com/teramonagi/sandbox-package-python.git
cd sandbox-package-python
pipenv install -e .
```
or 
```sh
pipenv install -e git+https://github.com/teramonagi/sandbox-package-python.git#egg=sandbox_package_python
```
See: https://github.com/pypa/pipenv#-usage

## Run
```sh
pipenv run python -c 'import sandbox_package_python; print(sandbox_package_python.hello())'
```
