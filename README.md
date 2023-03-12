# python-packaging

* Install twine by running pip install twine.
* Create a source distribution of your package by running python setup.py sdist. This will create a .tar.gz file in the dist directory.
* Create a wheel distribution of your package by running python setup.py bdist_wheel. This will create a .whl file in the dist directory.
* Upload your package to PyPI by running twine upload dist/*. You'll be prompted to enter your PyPI username and password.