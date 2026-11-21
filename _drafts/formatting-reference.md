---
title: Formatting reference
topic: Other
---
A cheat sheet for writing posts. Files in `_drafts/` are never published; preview this one locally with `jekyll serve --drafts`.

## Maths

Inline maths uses double dollar signs inside a sentence: the identity $$e^{i\pi} + 1 = 0$$ is a classic.

Put `$$...$$` on its own paragraph, with blank lines around it, for display maths:

$$
\int_0^\infty e^{-x^2}\,dx = \frac{\sqrt{\pi}}{2}
$$

Single dollar signs are left alone, so you can safely write that something costs $5 or $10.

## Code

```python
from functools import lru_cache

@lru_cache(maxsize=None)
def fib(n: int) -> int:
    """Return the n-th Fibonacci number."""
    return n if n < 2 else fib(n - 1) + fib(n - 2)

print([fib(i) for i in range(10)])  # first ten
```

Inline code looks like `fib(10)`.

## Footnotes

Footnotes collect at the bottom of the post.[^first] Write them anywhere in the file.[^second]

[^first]: Like this one, defined with `[^first]: ...`.
[^second]: They can contain *Markdown* and maths such as $$O(n \log n)$$.

