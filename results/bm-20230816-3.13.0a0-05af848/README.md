# Results

- fork: gvanrossum
- version: 3.13.0a0
- tier 2: False
- commit hash: [05af848](https://github.com/gvanrossum/cpython/commit/05af848)
- commit date: 2023-08-16T12:04:23-07:00
- commit merge base: [e28b0dc86dd1d058788b9e1eaa825cdfc2d97067](https://github.com/gvanrossum/cpython/commit/e28b0dc86dd1d058788b9e1eaa825cdfc2d97067)
- ref: call_uops

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5884114896)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-3.10.4.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 85.46%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-3.11.0.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.68%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-3.12.0.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 93.20%, 1.00x slower at 99th %ile)
- [table](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-base.md)
- [plot](bm-20230816-linux-x86_64-gvanrossum-call_uops-3.13.0a0-05af848-vs-base.png)

