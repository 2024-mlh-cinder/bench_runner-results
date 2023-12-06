# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [77a6830](https://github.com/brandtbucher/cpython/commit/77a6830)
- commit date: 2023-08-10T11:19:40-07:00
- commit merge base: [47d7eba889bc03884744f978f5f8612380363332](https://github.com/brandtbucher/cpython/commit/47d7eba889bc03884744f978f5f8612380363332)
- ref: kwnames_again_super

## linux x86_64 (azure)

- [pystats raw](bm-20230810-azure-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-pystats.json)
- [pystats table](bm-20230810-azure-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-pystats.md)

### vs. base

- [pystats diff](bm-20230810-azure-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6003761399)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-3.10.4.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 99.68%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-3.11.0.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-3.12.0.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-base.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again_super-3.13.0a0-77a6830-vs-base.png)

