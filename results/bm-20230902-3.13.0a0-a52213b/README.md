# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [a52213b](https://github.com/python/cpython/commit/a52213b)
- commit date: 2023-09-02T23:15:54+02:00
- ref: main

## linux x86_64 (azure)

- [pystats raw](bm-20230902-azure-x86_64-python-main-3.13.0a0-a52213b-pystats.json)
- [pystats table](bm-20230902-azure-x86_64-python-main-3.13.0a0-a52213b-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6061343267)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b-vs-3.10.4.md)
- [plot](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 82.78%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b-vs-3.11.0.md)
- [plot](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 98.59%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b-vs-3.12.0.md)
- [plot](bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6061343267)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b-vs-3.10.4.md)
- [plot](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 97.62%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b-vs-3.11.0.md)
- [plot](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 91.69%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b-vs-3.12.0.md)
- [plot](bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6061343267)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b.json)

### vs. 3.10.4

- Geometric mean: 1.14x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b-vs-3.10.4.md)
- [plot](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 83.59%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b-vs-3.11.0.md)
- [plot](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b-vs-3.12.0.md)
- [plot](bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6061343267)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b-vs-3.10.4.md)
- [plot](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 62.47%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b-vs-3.11.0.md)
- [plot](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 60.84%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b-vs-3.12.0.md)
- [plot](bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b-vs-3.12.0.png)

