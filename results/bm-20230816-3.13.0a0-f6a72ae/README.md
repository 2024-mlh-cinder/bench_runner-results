# Results

- fork: gvanrossum
- version: 3.13.0a0
- tier 2: False
- commit hash: [f6a72ae](https://github.com/gvanrossum/cpython/commit/f6a72ae)
- commit date: 2023-08-16T12:04:39-07:00
- commit merge base: [e28b0dc86dd1d058788b9e1eaa825cdfc2d97067](https://github.com/gvanrossum/cpython/commit/e28b0dc86dd1d058788b9e1eaa825cdfc2d97067)
- ref: call_uops_forever

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5882827909)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-3.10.4.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.88%, 1.01x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-3.11.0.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-3.12.0.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-base.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops_forever-3.13.0a0-f6a72ae-vs-base.png)

