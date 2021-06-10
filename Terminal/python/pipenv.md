```
sudo -H pip install -U pipenv
```

add path
```
PYTHON_BIN_PATH="$(python3 -m site --user-base)/bin"
PATH="$PATH:$PYTHON_BIN_PATH"
```