# Results

- fork: python
- version: 3.12.0+
- tier 2: False
- commit hash: [744f752](https://github.com/python/cpython/commit/744f752)
- commit date: 2023-10-14T14:28:58+00:00
- ref: 3.12

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6520828023)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752-vs-3.10.4.md)
- [plot](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752-vs-3.11.0.md)
- [plot](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752-vs-3.12.0.md)
- [plot](bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0%2B-744f752-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6520828023)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752.json)

### vs. 3.10.4

- Geometric mean: 1.17x faster \* (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752-vs-3.10.4.md)
- [plot](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 98.94%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752-vs-3.11.0.md)
- [plot](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 88.66%, 1.00x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752-vs-3.12.0.md)
- [plot](bm-20231014-pythonperf1-amd64-python-3.12-3.12.0%2B-744f752-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6520828023)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752-vs-3.10.4.md)
- [plot](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 62.76%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752-vs-3.11.0.md)
- [plot](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.91%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752-vs-3.12.0.md)
- [plot](bm-20231014-darwin-arm64-python-3.12-3.12.0%2B-744f752-vs-3.12.0.png)

