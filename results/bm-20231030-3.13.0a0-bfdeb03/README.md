# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [bfdeb03](https://github.com/brandtbucher/cpython/commit/bfdeb03)
- commit date: 2023-10-30T20:07:25-07:00
- commit merge base: [5bb6f0fcba663e1006f9063d1027ce8bd9f8effb](https://github.com/brandtbucher/cpython/commit/5bb6f0fcba663e1006f9063d1027ce8bd9f8effb)
- ref: justin_registers

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6711573601)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-3.10.4.md)
- [plot](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower (HPT: reliability of 99.31%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-3.11.0.md)
- [plot](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-3.12.0.md)
- [plot](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- new benchmarks: 2to3, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-base.md)
- [plot](bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03-vs-base.png)

