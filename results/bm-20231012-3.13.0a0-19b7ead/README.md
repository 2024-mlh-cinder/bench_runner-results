# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [19b7ead](https://github.com/python/cpython/commit/19b7ead)
- commit date: 2023-10-12T10:34:32+01:00
- ref: 19b7ead5eb2fd1a0d194

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6497410161)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead-vs-3.10.4.md)
- [plot](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 94.40%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead-vs-3.11.0.md)
- [plot](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 71.80%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead-vs-3.12.0.md)
- [plot](bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead-vs-3.12.0.png)

