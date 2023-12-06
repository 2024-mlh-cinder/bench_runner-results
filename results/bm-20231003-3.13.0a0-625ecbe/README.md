# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [625ecbe](https://github.com/python/cpython/commit/625ecbe)
- commit date: 2023-10-03T22:37:21+00:00
- ref: 625ecbe92eb69d2850c2

## linux x86_64 (azure)

- [pystats raw](bm-20231003-azure-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-pystats.json)
- [pystats table](bm-20231003-azure-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6399914137)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-vs-3.10.4.md)
- [plot](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 90.35%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-vs-3.11.0.md)
- [plot](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 97.34%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-vs-3.12.0.md)
- [plot](bm-20231003-linux-x86_64-python-625ecbe92eb69d2850c2-3.13.0a0-625ecbe-vs-3.12.0.png)

