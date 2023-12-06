# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [5bb6f0f](https://github.com/python/cpython/commit/5bb6f0f)
- commit date: 2023-09-27T15:27:44-07:00
- ref: 5bb6f0fcba663e1006f9

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6344655178)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f-vs-3.10.4.md)
- [plot](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 88.18%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f-vs-3.11.0.md)
- [plot](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 93.07%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f-vs-3.12.0.md)
- [plot](bm-20230927-linux-x86_64-python-5bb6f0fcba663e1006f9-3.13.0a0-5bb6f0f-vs-3.12.0.png)

