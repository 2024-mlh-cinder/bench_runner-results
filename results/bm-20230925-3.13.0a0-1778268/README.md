# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [1778268](https://github.com/brandtbucher/cpython/commit/1778268)
- commit date: 2023-09-25T14:44:05-07:00
- commit merge base: [5bb6f0fcba663e1006f9063d1027ce8bd9f8effb](https://github.com/brandtbucher/cpython/commit/5bb6f0fcba663e1006f9063d1027ce8bd9f8effb)
- ref: justin_registers

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6347202432)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-3.10.4.md)
- [plot](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 96.56%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-3.11.0.md)
- [plot](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.77%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-3.12.0.md)
- [plot](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-base.md)
- [plot](bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268-vs-base.png)

