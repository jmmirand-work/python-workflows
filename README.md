# python-workflows

Mis propios Workflows asociados a Python

## Build and Test

Este workflows consturye y ejecuta los test que tengamos implementado.

* No necesita variables de entrada ni secretos.
* La estructura del proyecto

``` text
proyecto_path\
                Pipfile

                src\
                      file1.py
                      file2.py
                test\
                      init-test.sh
                      test1.py

```

* Uso

``` yaml
    jobs:
    cw-build-and-test-python:
        uses: jmmirand-work/python-workflows/.github/workflows/build_and_test.yaml@main
```
