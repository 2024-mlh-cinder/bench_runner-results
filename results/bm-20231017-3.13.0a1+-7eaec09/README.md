# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: False
- commit hash: [7eaec09](https://github.com/brandtbucher/cpython/commit/7eaec09)
- commit date: 2023-10-17T16:22:05-07:00
- commit merge base: [f07ca27709855d4637b43bba23384cc795143ee3](https://github.com/brandtbucher/cpython/commit/f07ca27709855d4637b43bba23384cc795143ee3)
- ref: justin

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.md)
- [plot](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 99.47%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.md)
- [plot](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.md)
- [plot](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.md)
- [plot](bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.19x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.md)
- [plot](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 78.76%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.md)
- [plot](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.md)
- [plot](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.md)
- [plot](bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09.json)

### vs. 3.10.4

- Geometric mean: 1.08x faster \* (HPT: reliability of 99.99%, 1.02x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.md)
- [plot](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.83%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.md)
- [plot](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.10x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.md)
- [plot](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.md)
- [plot](bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6562807196)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, regex_compile, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.md)
- [plot](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 65.03%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, regex_compile, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.md)
- [plot](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 50.50%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, pprint_pformat, pprint_safe_repr, regex_compile, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.md)
- [plot](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- missing benchmarks: 🔴 pprint_pformat, pprint_safe_repr, regex_compile
- [table](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.md)
- [plot](bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7eaec09-vs-base.png)

