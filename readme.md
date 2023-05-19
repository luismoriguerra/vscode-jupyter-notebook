## Get started with Python

python -m ensurepip --upgrade
python -m pip install --upgrade pip
python -m pip install --upgrade virtualenv

## Get Started environment

python -m venv .environ
source .environ/bin/activate
pip install -r requirements.txt

## deactivate environment

deactivate

## First time with jupyter notebook

pip install ipykernel
python -m ipykernel install --user --name=env

## Dependencies

pip freeze > requirements.txt
pip install --upgrade -r requirements.txt

## Using inline sql

https://medium.com/analytics-vidhya/postgresql-integration-with-jupyter-notebook-deb97579a38d
