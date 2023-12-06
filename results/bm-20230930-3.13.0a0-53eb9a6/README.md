# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [53eb9a6](https://github.com/python/cpython/commit/53eb9a6)
- commit date: 2023-09-30T22:37:23+00:00
- ref: main

## linux x86_64 (azure)

- [pystats raw](bm-20230930-azure-x86_64-python-main-3.13.0a0-53eb9a6-pystats.json)
- [pystats table](bm-20230930-azure-x86_64-python-main-3.13.0a0-53eb9a6-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.md)
- [plot](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 99.26%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.md)
- [plot](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.md)
- [plot](bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.md)
- [plot](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 93.96%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.md)
- [plot](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 97.61%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.md)
- [plot](bm-20230930-pythonperf2-x86_64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6.json)

### vs. 3.10.4

- Geometric mean: 1.17x faster \* (HPT: reliability of 100.00%, 1.10x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.md)
- [plot](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 99.16%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.md)
- [plot](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 92.81%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.md)
- [plot](bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.md)
- [plot](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 70.02%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.md)
- [plot](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 95.15%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.md)
- [plot](bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6-vs-3.12.0.png)

