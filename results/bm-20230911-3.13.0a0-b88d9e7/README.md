# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [b88d9e7](https://github.com/python/cpython/commit/b88d9e7)
- commit date: 2023-09-11T17:11:06-07:00
- ref: b88d9e75f68f102aca45

## linux x86_64 (azure)

- [pystats raw](bm-20230911-azure-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-pystats.json)
- [pystats table](bm-20230911-azure-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6153844490)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-vs-3.10.4.md)
- [plot](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 95.70%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-vs-3.11.0.md)
- [plot](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.05%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-vs-3.12.0.md)
- [plot](bm-20230911-linux-x86_64-python-b88d9e75f68f102aca45-3.13.0a0-b88d9e7-vs-3.12.0.png)

