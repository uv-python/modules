Repository of installable (pip) Python modules.
(PyPI does not accept new registrations).

To install:

```pip3 install https://github.com/uv-python/modules/raw/main/modules/<wheel file name>```

E.g.
```
pip3 install https://github.com/uv-python/modules/raw/main/modules/dyn_dispatch-0.3-py3-none-any.whl
```
URLs can be added directly inside `requirements.txt` files:

`requirements.txt`:
```
...
# dyn_dispatch version 0.3
https://github.com/uv-python/modules/raw/main/modules/dyn_dispatch-0.3-py3-none-any.whl
```
```pip3 -r requirements.txt```
