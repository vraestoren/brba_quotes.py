<div align="center">
  <img src="https://breakingbadquotes.xyz/img/logo.png" width="120" />

# brba_quotes.py

> Web-API for [Breaking Bad Quotes](https://breakingbadquotes.xyz) a REST API to retrieve quotes from the Breaking Bad universe.

</div>

## Quick Start

```python
from brba_quotes import BrBaQuotes

brba = BrBaQuotes()

# Get a random quote
print(brba.get_random_quote())

# Get 5 random quotes
print(brba.get_multiple_quotes(5))
```

---

<div align="center">

## Quotes

| Method | Description |
|--------|-------------|
| `get_random_quote()` | Get a single random quote |
| `get_multiple_quotes(count)` | Get multiple random quotes |

</div>
