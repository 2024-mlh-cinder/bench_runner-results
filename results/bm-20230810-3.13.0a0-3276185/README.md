# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [3276185](https://github.com/brandtbucher/cpython/commit/3276185)
- commit date: 2023-08-10T04:01:02-07:00
- commit merge base: [4eae1e53425d3a816a26760f28d128a4f05c1da4](https://github.com/brandtbucher/cpython/commit/4eae1e53425d3a816a26760f28d128a4f05c1da4)
- ref: kwnames_again

## linux x86_64 (azure)

- [pystats raw](bm-20230810-azure-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-pystats.json)
- [pystats table](bm-20230810-azure-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-pystats.md)

### vs. base

- [pystats diff](bm-20230810-azure-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5982619490)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-3.10.4.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 80.32%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-3.11.0.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 82.54%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-3.12.0.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-base.md)
- [plot](bm-20230810-linux-x86_64-brandtbucher-kwnames_again-3.13.0a0-3276185-vs-base.png)

