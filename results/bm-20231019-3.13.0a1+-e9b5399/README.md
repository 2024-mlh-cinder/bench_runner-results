# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [e9b5399](https://github.com/python/cpython/commit/e9b5399)
- commit date: 2023-10-19T09:29:45+01:00
- ref: e9b5399bee7106beeeb3

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6617043156)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399-vs-3.10.4.md)
- [plot](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 71.48%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399-vs-3.11.0.md)
- [plot](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 95.38%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399-vs-3.12.0.md)
- [plot](bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1%2B-e9b5399-vs-3.12.0.png)

