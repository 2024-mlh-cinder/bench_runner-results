# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [f07ca27](https://github.com/python/cpython/commit/f07ca27)
- commit date: 2023-10-16T19:52:13+01:00
- ref: f07ca27709855d4637b4

## linux x86_64 (azure)

- [pystats raw](bm-20231016-azure-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-pystats.json)
- [pystats table](bm-20231016-azure-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.md)
- [plot](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 85.15%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.md)
- [plot](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 96.70%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.md)
- [plot](bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.md)
- [plot](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 96.70%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.md)
- [plot](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 93.61%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.md)
- [plot](bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27.json)

### vs. 3.10.4

- Geometric mean: 1.13x faster \* (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.md)
- [plot](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 78.48%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.md)
- [plot](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.md)
- [plot](bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.md)
- [plot](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 54.22%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.md)
- [plot](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 83.45%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.md)
- [plot](bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1%2B-f07ca27-vs-3.12.0.png)

