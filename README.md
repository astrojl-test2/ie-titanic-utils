# ie-titanic-utils
Sample project for Python Workshop (IE MBD)

(Full description to be completed)

(With extra information)

## Install

To install:

```
$ pip install .
```

## Development

To develop more conveniently:

```
$ pip install -e .
```

## Solutions

1. VERY BAD: "*Just* go to `/workspace/ie-titanic-utils`"
   - Con: Your users will start polluting everything
2. QUITE BAD: I send the file (`str_utils.py`) and the user puts it in their working directory
   - If they're working on several directories
   - You don't control the code anymore
3. A LITTLE BIT BAD: Change `sys.path`
   - Users use the development version
4. EXCELLENT: Attending the rest of the course

## Python installation

```
pyenv
|
|- miniforge3 (once per machine)
   |
   |- conda
      |
      | - create an environment (once per project)
          |
          | - Isolated Python installation with both conda and pip (every day)
```

Anaconda Inc. != Anaconda Distribution != conda

```
Anaconda Inc. (company)
|
|- Anaconda Distribution (product)
   |
   |- conda (software)
   |- pandas
   |- scikit-learn
   |- ...
```
