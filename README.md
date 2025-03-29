# Pyright namespace issue

This is a minimal working example of a pyright namespace issue. It requires [poetry](https://python-poetry.org/) to run the example as shown below.

To show the issue run

```bash
poetry install
poetry run pyright ./example_script.py
```

in your shell which in my shell outputs

> \<ROOT-DIRECTORY>\pyright-namespace-issue\example_script.py  
> \<ROOT-DIRECTORY>\pyright-namespace-issue\example_script.py:1:6 - error: Stub file not found for "namespace" (reportMissingTypeStubs)  
> 1 error, 0 warnings, 0 informations
