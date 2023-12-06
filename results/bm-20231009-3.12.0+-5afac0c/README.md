# Results

- fork: python
- version: 3.12.0+
- tier 2: False
- commit hash: [5afac0c](https://github.com/python/cpython/commit/5afac0c)
- commit date: 2023-10-09T11:43:35+00:00
- ref: 3.12

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6444347438)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c-vs-3.10.4.md)
- [plot](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 72.05%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c-vs-3.11.0.md)
- [plot](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 87.32%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c-vs-3.12.0.md)
- [plot](bm-20231009-darwin-arm64-python-3.12-3.12.0%2B-5afac0c-vs-3.12.0.png)

