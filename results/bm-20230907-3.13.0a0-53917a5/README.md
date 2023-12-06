# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [53917a5](https://github.com/brandtbucher/cpython/commit/53917a5)
- commit date: 2023-09-07T20:52:55-07:00
- commit merge base: [b88d9e75f68f102aca45fa62e2b0e2e2ff46d810](https://github.com/brandtbucher/cpython/commit/b88d9e75f68f102aca45fa62e2b0e2e2ff46d810)
- ref: call_kw

## linux x86_64 (azure)

- [pystats raw](bm-20230907-azure-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-pystats.json)
- [pystats table](bm-20230907-azure-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6153844490)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-3.10.4.md)
- [plot](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 97.40%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-3.11.0.md)
- [plot](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-3.12.0.md)
- [plot](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 99.82%, 1.00x faster at 99th %ile)
- [table](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-base.md)
- [plot](bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5-vs-base.png)

