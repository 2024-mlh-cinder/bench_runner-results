# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [70d0242](https://github.com/brandtbucher/cpython/commit/70d0242)
- commit date: 2023-08-11T02:59:40-07:00
- commit merge base: [47d7eba889bc03884744f978f5f8612380363332](https://github.com/brandtbucher/cpython/commit/47d7eba889bc03884744f978f5f8612380363332)
- ref: kwnames_tstate

## linux x86_64 (azure)

- [pystats raw](bm-20230811-azure-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-pystats.json)
- [pystats table](bm-20230811-azure-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-pystats.md)

### vs. base

- [pystats diff](bm-20230811-azure-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6018842536)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-3.10.4.md)
- [plot](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 52.67%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-3.11.0.md)
- [plot](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 59.77%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-3.12.0.md)
- [plot](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-base.md)
- [plot](bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242-vs-base.png)

