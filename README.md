# pybind11 Example

This is a minimal pybind11 example that exposes a simple `add` function to Python.

## Build

```bash
python -m pip install pybind11 setuptools
python setup.py build_ext --inplace
```

## Usage

```python
import example
print(example.add(2, 3))
```
