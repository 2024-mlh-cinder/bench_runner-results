# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [74fc96b](https://github.com/python/cpython/commit/74fc96b)
- commit date: 2023-09-07T11:34:18-07:00
- ref: 74fc96bc60f5c02bde50

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6116272281)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b-vs-3.10.4.md)
- [plot](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 86.69%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b-vs-3.11.0.md)
- [plot](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 97.14%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b-vs-3.12.0.md)
- [plot](bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b-vs-3.12.0.png)

