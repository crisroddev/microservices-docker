setup:
	# Create python virtualenv & source it
	# source ~/.udacity-devops/bin/activate
	python3 -m venv ~/.udacity-devops

install:
	# This should be run from inside a virtualenv
	pip install --upgrade pip &&\
		pip install -r requirements.txt

test:
	# Additional, optional, tests could go here
	#python -m pytest -vv --cov=myrepolib tests/*.py
	#python -m pytest --nbval notebook.ipynb

lint:
	hadolint Dockerfile
	#pylint --disable=R,C,W1203,DL3013 app.py

validate-circleci:
	circleci config process .circleci/config.yml

run-cirlce-ci-local:
	circleci local execute

all: install lint test
