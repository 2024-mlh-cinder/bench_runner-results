# Results

- fork: gvanrossum
- version: 3.13.0a0
- tier 2: False
- commit hash: [1850988](https://github.com/gvanrossum/cpython/commit/1850988)
- commit date: 2023-09-07T17:21:32-07:00
- commit merge base: [74fc96bc60f5c02bde50ff2f3516add99483e402](https://github.com/gvanrossum/cpython/commit/74fc96bc60f5c02bde50ff2f3516add99483e402)
- ref: count_branches

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6116272281)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-3.10.4.md)
- [plot](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 88.75%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-3.11.0.md)
- [plot](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.88%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-3.12.0.md)
- [plot](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 56.52%, 1.00x slower at 99th %ile)
- [table](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-base.md)
- [plot](bm-20230907-linux-x86_64-gvanrossum-count_branches-3.13.0a0-1850988-vs-base.png)

