# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [2928e5d](https://github.com/python/cpython/commit/2928e5d)
- commit date: 2023-08-30T16:02:48+02:00
- ref: 2928e5dc6512e4206c61

## linux x86_64 (azure)

- [pystats raw](bm-20230830-azure-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-pystats.json)
- [pystats table](bm-20230830-azure-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6035390507)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.10.4.md)
- [plot](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 84.16%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.11.0.md)
- [plot](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 95.66%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.12.0.md)
- [plot](bm-20230830-linux-x86_64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6047222418)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.10.4.md)
- [plot](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 71.28%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.11.0.md)
- [plot](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.92%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.12.0.md)
- [plot](bm-20230830-pythonperf1-amd64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6047226291)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.10.4.md)
- [plot](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.65%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.11.0.md)
- [plot](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.55%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.12.0.md)
- [plot](bm-20230830-darwin-arm64-python-2928e5dc6512e4206c61-3.13.0a0-2928e5d-vs-3.12.0.png)

