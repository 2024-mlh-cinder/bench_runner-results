# Results

- fork: iritkatriel
- version: 3.13.0a1+
- tier 2: False
- commit hash: [90d6409](https://github.com/iritkatriel/cpython/commit/90d6409)
- commit date: 2023-10-20T13:53:54+01:00
- commit merge base: [e9b5399bee7106beeeb38a45cfef3f0ed3fdd703](https://github.com/iritkatriel/cpython/commit/e9b5399bee7106beeeb38a45cfef3f0ed3fdd703)
- ref: refleak

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6617043156)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-3.10.4.md)
- [plot](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 61.21%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-3.11.0.md)
- [plot](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 72.43%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-3.12.0.md)
- [plot](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 99.85%, 1.00x faster at 99th %ile)
- [table](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-base.md)
- [plot](bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1%2B-90d6409-vs-base.png)

