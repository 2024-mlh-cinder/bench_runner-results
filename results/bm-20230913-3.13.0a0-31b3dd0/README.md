# Results

- fork: iritkatriel
- version: 3.13.0a0
- tier 2: False
- commit hash: [31b3dd0](https://github.com/iritkatriel/cpython/commit/31b3dd0)
- commit date: 2023-09-13T13:33:03+01:00
- commit merge base: [d69805b38a1815e7aaadf49bdd019c7cca105ac6](https://github.com/iritkatriel/cpython/commit/d69805b38a1815e7aaadf49bdd019c7cca105ac6)
- ref: INSTRUMENTED_LINE

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6172892023)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-3.10.4.md)
- [plot](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 95.49%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-3.11.0.md)
- [plot](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.93%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-3.12.0.md)
- [plot](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 86.99%, 1.00x slower at 99th %ile)
- [table](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-base.md)
- [plot](bm-20230913-linux-x86_64-iritkatriel-INSTRUMENTED_LINE-3.13.0a0-31b3dd0-vs-base.png)

