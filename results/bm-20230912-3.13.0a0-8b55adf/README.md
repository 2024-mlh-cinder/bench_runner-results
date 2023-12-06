# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [8b55adf](https://github.com/python/cpython/commit/8b55adf)
- commit date: 2023-09-12T10:36:17+00:00
- ref: 8b55adfa8ff05477b4be

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6173499880)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.10.4.md)
- [plot](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 90.58%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.11.0.md)
- [plot](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 96.48%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.12.0.md)
- [plot](bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6300186313)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.10.4.md)
- [plot](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 98.36%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.11.0.md)
- [plot](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 83.93%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.12.0.md)
- [plot](bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf-vs-3.12.0.png)

