# What
I took the code at https://www.unixuser.org/~euske/doc/cdbinternals/pycdb.py.html and made it Python 3 compatible.
[Yusuke Shinyama](https://www.github.com/euske) here on github.

I also replaced https://github.com/acg/python-cdb (now unmaintained) with https://python-pure-cdb.readthedocs.io/en/latest/

# Why?
I wanted to write a [port of CDB to Swift](https://github.com/createthis/swift-cdb) for a work project and 
the `cdbget` function in this code is the cleanest and least choppy (broken up into separate functions) version 
I could find anywhere on the internet.

# Getting Started

```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
```

# Run
```bash
python3 pycdb.py
```
