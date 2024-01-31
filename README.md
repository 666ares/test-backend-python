# test-backend-python

[Git-Flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
[Pipenv](https://pipenv-es.readthedocs.io/es/latest/basics.html)

```bash
pipenv install --python 3.10
pipenv shell
pipenv install --dev pipenv==2023.11.17
pipenv install --dev tox==3.28.0
pipenv install --dev tox-pipenv==1.10.1
```

tox-pipenv no funciona para versiones de Tox posteriores a la 4.
https://www.kianmeng.org/2023/01/importerror-cannot-import-name-hookimpl.html
