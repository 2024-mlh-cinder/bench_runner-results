# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [6c13e13](https://github.com/python/cpython/commit/6c13e13)
- commit date: 2023-09-13T10:26:50-07:00
- ref: 6c13e13b13bebfdde8ad

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6181045878)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.md)
- [plot](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 97.14%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.md)
- [plot](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.31%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.md)
- [plot](bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6181045878)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.20x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.md)
- [plot](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 97.02%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.md)
- [plot](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 97.35%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.md)
- [plot](bm-20230913-pythonperf2-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6181045878)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.md)
- [plot](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 75.09%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.md)
- [plot](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.96%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.md)
- [plot](bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6181045878)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.md)
- [plot](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 63.00%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.md)
- [plot](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 68.22%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.md)
- [plot](bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13-vs-3.12.0.png)

