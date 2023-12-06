# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [8e56d55](https://github.com/python/cpython/commit/8e56d55)
- commit date: 2023-10-07T17:07:36-07:00
- ref: main

## linux x86_64 (azure)

- [pystats raw](bm-20231007-azure-x86_64-python-main-3.13.0a0-8e56d55-pystats.json)
- [pystats table](bm-20231007-azure-x86_64-python-main-3.13.0a0-8e56d55-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6444347438)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55-vs-3.10.4.md)
- [plot](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 82.50%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55-vs-3.11.0.md)
- [plot](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 98.71%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55-vs-3.12.0.md)
- [plot](bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6444347438)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55-vs-3.10.4.md)
- [plot](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 97.48%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55-vs-3.11.0.md)
- [plot](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 81.39%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55-vs-3.12.0.md)
- [plot](bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6444347438)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55.json)

### vs. 3.10.4

- Geometric mean: 1.17x faster \* (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55-vs-3.10.4.md)
- [plot](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 74.43%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55-vs-3.11.0.md)
- [plot](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.95%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55-vs-3.12.0.md)
- [plot](bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55-vs-3.12.0.png)

