# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [6c23635](https://github.com/python/cpython/commit/6c23635)
- commit date: 2023-10-21T22:18:34+03:00
- ref: main

## linux x86_64 (azure)

- [pystats raw](bm-20231021-azure-x86_64-python-main-3.13.0a1%2B-6c23635-pystats.json)
- [pystats table](bm-20231021-azure-x86_64-python-main-3.13.0a1%2B-6c23635-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6600546763)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.md)
- [plot](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 61.93%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.md)
- [plot](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 91.06%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.md)
- [plot](bm-20231021-linux-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6600546763)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.md)
- [plot](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 86.42%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.md)
- [plot](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 98.93%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.md)
- [plot](bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6600546763)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635.json)

### vs. 3.10.4

- Geometric mean: 1.14x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.md)
- [plot](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 53.47%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.md)
- [plot](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.md)
- [plot](bm-20231021-pythonperf1-amd64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6600546763)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.md)
- [plot](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 52.35%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.md)
- [plot](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 83.34%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.md)
- [plot](bm-20231021-darwin-arm64-python-main-3.13.0a1%2B-6c23635-vs-3.12.0.png)

