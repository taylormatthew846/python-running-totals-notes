# Calculate prefix sums: implementation

## What the example does

accumulate emits the running total after each item. Integer arithmetic is exact; floating-point totals may accumulate rounding error.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
[
  1,
  2,
  3
]
```

Expected result:

```json
[
  1,
  3,
  6
]
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
