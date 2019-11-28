**Activate the virtual environment**

```
source blockchain-env/bin/activate
```

**Install all packages**

```
pip3 install -r requirements.txt
```

**Run the tests**

Make sure to activate the virtual environment.

```
python3 -m pytest backend/tests
```

**Run the app and API**
make sure to activate the virtual environment

```
python -m backend.app
```

**Run a peer instance**
Make sure to activate the VE

```
export PEER=True && python -m backend.app
```
