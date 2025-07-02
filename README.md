# packaging-hello-world

A repo to test the behavior of various Python packaging tools:

* setuptools
* pbr

## Usage

Create a virtualenv and install `build`:

```
virtualenv .venv
source .venv/bin/activate
pip install build
```

Once done, you can experiment. For example, to build an sdist with pbr:

```
cd pbr
python -m build --sdist
```
