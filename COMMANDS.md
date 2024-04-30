```shell
# create virtual environment
python -m venv env
```

```shell
# activate environment
source ./env/bin/activate
```

```shell
# deactivate environment
deactivate
```

```shell
# install dependencies
pip install -r requirements.txt
```

```shell
# run server
uvicorn main:app --reload
```
