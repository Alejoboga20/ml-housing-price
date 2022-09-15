# Housing Price Predictions using Machine Learning

## Setup

1. Create a Python virtual environment

```bash
$ python3 -m venv venv
```

2. Activate virtual environment

```bash
$ source venv/bin/activate
# If environemnts it's active you should see (venv) at your prompt
```

3. Install Dependencies in **requirements.txt** file

```bash
$ pip install -r requirements.txt
# if new packages are added please run the following to keep requirements.txt updated
$ pip freeze > requirements.txt
```

4. To use venv in jupyter notebook you need to register it:

```bash
$ pip install ipykernel
$ python -m ipykernel install --user --name=venv
# After this venv should be available in jupyter notebook
```

5. Run Jupyter Notebook

```bash
$ jupyter notebook
```

6. A Jupyter server is now running in your terminal, listening to port 8888. You can visit this server by opening your web browser to http://localhost:8888.

7. To deactivate virtual environment use:

```bash
$ deactivate
```
