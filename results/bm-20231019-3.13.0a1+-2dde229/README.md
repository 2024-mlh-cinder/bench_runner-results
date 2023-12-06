# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: False
- commit hash: [2dde229](https://github.com/brandtbucher/cpython/commit/2dde229)
- commit date: 2023-10-19T19:17:27-07:00
- commit merge base: [f07ca27709855d4637b43bba23384cc795143ee3](https://github.com/brandtbucher/cpython/commit/f07ca27709855d4637b43bba23384cc795143ee3)
- ref: break_up_float_reuse

## linux x86_64 (azure)

- [pystats raw](bm-20231019-azure-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-pystats.json)
- [pystats table](bm-20231019-azure-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-pystats.md)

### vs. base

- [pystats diff](bm-20231019-azure-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6582593395)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.20x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-3.10.4.md)
- [plot](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 95.95%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-3.11.0.md)
- [plot](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.72%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-3.12.0.md)
- [plot](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 99.95%, 1.00x slower at 99th %ile)
- [table](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-base.md)
- [plot](bm-20231019-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1%2B-2dde229-vs-base.png)

