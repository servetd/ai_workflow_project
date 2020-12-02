# AI Enterprise Workflow Project

This project uses time series to forecast revenue prediction for the next 30 days.

# Usage notes

All commands are from this directory.

## To test `app.py`

```bash
~$ python app.py
```

or to start the flask app in debug mode

```bash
~$ python app.py -d
```

Go to http://127.0.0.1:8080/ and you will see a basic website that can be customtized for a project.
    
## To test the model directly and train the model

see the code at the bottom of `model.py`

```bash
~$ python model.py
```

## Run the unittests

Before running the unit tests launch the `app.py`.

To run only the api tests

```bash
~$ python unittests/ApiTests.py
```

To run only the model tests

```bash
~$ python unittests/ModelTests.py
```

To run all of the tests

```bash
~$ python run-tests.py
```

