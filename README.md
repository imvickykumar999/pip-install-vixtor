# vixtor

## pip install vixtor

#### ...made with love and hardwork ;)
#### [Post on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:6715639149992394752/)

[![pypi](https://raw.githubusercontent.com/imvickykumar999/vixtor/master/pypi.png)](https://pypi.org/project/vixtor/)

# Package : Vixtor = Vix (my nickname) + 3D_Vector

...this package can solve most of the questions of chapter 11, [NCERT](https://github.com/imvickykumar999/vixtor/blob/master/NCERT-Books-for-class%2012-Maths-Chapter%2011.pdf) (3D Vector) of class 12th.

...checkout my linkedin post for tutorial on how to use package's function and fully explained by solving questions.

...repo on github ( username : imvickykumar999 )

![plane](https://raw.githubusercontent.com/imvickykumar999/vixtor/master/vixtor.png)

# How to Upload to PyPi :

1. creating a folder: any name
2. creating a sub folder : vector
3. creating a sub folder : vixtor
4. create __init__.py inside 2nd folder
5. create setup.py inside 1st folder
6. pip install setuptools
7. import setuptools
8. define setup configuration inside setup.py file
9. include manifest.in
10. include readme.txt
11. include license.txt
13. run 'python setup.py sdist' cmd in terminal
14. install twine package :'pip install twine'
15. twine upload dist/*
or, python3 -m twine upload --repository-url https://test.pypi.org/legacy/ dist/*
16. Enter your PyPi username and then password.
