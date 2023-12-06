# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [66bea25](https://github.com/python/cpython/commit/66bea25)
- commit date: 2023-10-29T00:01:53+01:00
- ref: main

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6680087424)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.md)
- [plot](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster (HPT: reliability of 99.94%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.md)
- [plot](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.md)
- [plot](bm-20231029-linux-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6680087424)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.md)
- [plot](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster (HPT: reliability of 96.55%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.md)
- [plot](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower (HPT: reliability of 99.98%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.md)
- [plot](bm-20231029-pythonperf2-x86_64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6680087424)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- missing benchmarks: aiohttp, coverage, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.md)
- [plot](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster (HPT: reliability of 58.05%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, coverage, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.md)
- [plot](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, coverage, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.md)
- [plot](bm-20231029-pythonperf1-amd64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6680087424)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.md)
- [plot](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 91.89%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.md)
- [plot](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 63.55%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.md)
- [plot](bm-20231029-darwin-arm64-python-main-3.13.0a1%2B-66bea25-vs-3.12.0.png)

