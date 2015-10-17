django-compress-react
=====================

In order to easily use react.js in Django in a more pure Python way.


logging
-------

Logging isn't readily available but an environment variable can be set to invoke print statements:

```bash
REACT_DEBUG=True
```

Any value is technically valid as it just looks for it to be set.


Example:
--------

```python
COMPRESS_PRECOMPILERS = (
    ('text/jsx', 'compress_react.ReactFilter'),
)
```