# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [9d7c25a](https://github.com/brandtbucher/cpython/commit/9d7c25a)
- commit date: 2023-09-06T03:42:13-07:00
- commit merge base: [deea7c82682848b2a0db971a4dcc3a32c73a9f8c](https://github.com/brandtbucher/cpython/commit/deea7c82682848b2a0db971a4dcc3a32c73a9f8c)
- ref: justin_opargs

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6105430365)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.md)
- [plot](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 96.66%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.md)
- [plot](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.97%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.md)
- [plot](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.md)
- [plot](bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6105430365)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.md)
- [plot](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 78.06%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.md)
- [plot](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.md)
- [plot](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.md)
- [plot](bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6105430365)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a.json)

### vs. 3.10.4

- Geometric mean: 1.11x faster \* (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.md)
- [plot](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 99.56%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.md)
- [plot](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.md)
- [plot](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.md)
- [plot](bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6105430365)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.md)
- [plot](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 98.05%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.md)
- [plot](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.55%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.md)
- [plot](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.md)
- [plot](bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a-vs-base.png)

