# CONTRIBUTING

## Guidelines
- fork the project
- clone the forked project
- create a virtual environment directory with command `$ python -m venv .venv`
- activate the newly made virtual environment with `$ ./.venv/Scripts/activate` in windows and `$ source ./.venv/bin/activate` on linux or mac
- You can simply do all the installs once with command `$ pip install -r requirements.txt` OR you can install these mannually
- pip install the nepali_date in editable mode. On the root directory of project do `$ pip install -e .`
- install `pytest` for running tests. ```$ pip install pytest```
- install `flake8` for code formatting check. ```$ pip install flake8```
- check if all tests are passed by ```$ pytest```
- start contributing
- before pushing the changes check again if the tests are passed ```$ pytest```
- also check code formatting has any issues `$ flake8 nepali_datetime --max-line-length=120`
- push your code and raise PR

**Note: If you're confused on what to contribute in for, you can search for *TODO's* in the code & pick up which ever
you're comfortable with.**


#### *** HAPPY CONTRIBUTING ! ***
