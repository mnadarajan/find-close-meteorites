# find-close-meteorites
A demo project that uses Python and NASA data to find meteor landing sites

## Running

This project requires Python 3 and the requests packages

First install pipenv. python_version
'''
pipenv install
pipenv run "python meteors/find_meteors.py"


Notes:
pipenv install --skip-lock request      # --skip-lock used because there was lock error
pipenv install --skip-lock -d ipython   # -d is only for development. it will no be moved to package
'''
