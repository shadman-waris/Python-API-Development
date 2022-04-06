# Python API Development

## Installation

- Creating a [python virtual environment](https://docs.python.org/3/library/venv.html) 

```bash
python3 -m venv <name> 
```

example: 

python3 -m venv venv

then enable the virtual environment for command line

```bash
source venv/bin/activate 
```

then install fastapi package

```bash
pip install fastapi[all]
```

to run live server 

```bash
uvicorn app.main:app --reload
```
 
