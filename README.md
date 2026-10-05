# first-pr-practice

A tiny calculator library used to practise opening a first pull request.

## Installation

No dependencies are required. Just clone the repository:

```
gh repo clone epapzp2071-boop/first-pr-practice
```

## Usage

```python
from calculator import add, divide

add(2, 3)      # 5
divide(10, 4)  # 2.5
```

Dividing by zero will raise a `ValueError` so you receive a clear error message.

## Running tests

```
python -m unittest -v
```
