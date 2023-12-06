# Results

- fork: python
- version: 3.12.0rc3+
- tier 2: False
- commit hash: [8882b30](https://github.com/python/cpython/commit/8882b30)
- commit date: 2023-09-29T15:31:10+02:00
- ref: 3.12

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.md)
- [plot](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 71.92%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.md)
- [plot](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.99%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.md)
- [plot](bm-20230929-linux-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.md)
- [plot](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.43%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.md)
- [plot](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 74.48%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.md)
- [plot](bm-20230929-pythonperf2-x86_64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster \* (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.md)
- [plot](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.md)
- [plot](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.90%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.md)
- [plot](bm-20230929-pythonperf1-amd64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6366652790)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.md)
- [plot](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 63.44%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.md)
- [plot](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.md)
- [plot](bm-20230929-darwin-arm64-python-3.12-3.12.0rc3%2B-8882b30-vs-3.12.0.png)

