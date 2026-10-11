# json-flatten

Utilities for turning nested dictionaries into dotted keys and back.

## Why

I wanted something I could read in one sitting and vendor into a project if needed.

## Install

```bash
pip install json-flatten
```

## Usage

```python
from json_flatten import jsonFlatten

result = jsonFlatten("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
