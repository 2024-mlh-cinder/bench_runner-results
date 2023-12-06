# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [9c8ccf6](https://github.com/brandtbucher/cpython/commit/9c8ccf6)
- commit date: 2023-09-05T15:10:26-07:00
- commit merge base: [deea7c82682848b2a0db971a4dcc3a32c73a9f8c](https://github.com/brandtbucher/cpython/commit/deea7c82682848b2a0db971a4dcc3a32c73a9f8c)
- ref: call_kw

## linux x86_64 (azure)

- [pystats raw](bm-20230905-azure-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-pystats.json)
- [pystats table](bm-20230905-azure-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-pystats.md)

### vs. base

- [pystats diff](bm-20230905-azure-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6090269467)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-3.10.4.md)
- [plot](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 89.36%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-3.11.0.md)
- [plot](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 98.05%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-3.12.0.md)
- [plot](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 94.94%, 1.00x faster at 99th %ile)
- [table](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-base.md)
- [plot](bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6-vs-base.png)

