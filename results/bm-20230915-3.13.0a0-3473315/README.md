# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [3473315](https://github.com/brandtbucher/cpython/commit/3473315)
- commit date: 2023-09-15T15:54:21-07:00
- commit merge base: [909adb5092c0ae9426814742d97932204b211cfb](https://github.com/brandtbucher/cpython/commit/909adb5092c0ae9426814742d97932204b211cfb)
- ref: justin_no_pic

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6203581720)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-3.10.4.md)
- [plot](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 73.45%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-3.11.0.md)
- [plot](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 80.06%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-3.12.0.md)
- [plot](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 99.87%, 1.00x slower at 99th %ile)
- [table](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-base.md)
- [plot](bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315-vs-base.png)

