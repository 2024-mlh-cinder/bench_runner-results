# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [853b4b5](https://github.com/python/cpython/commit/853b4b5)
- commit date: 2023-11-04T23:05:22+00:00
- commit merge base: [a6c1c04d4d2339f0094422974ae3f26f8c7c8565](https://github.com/python/cpython/commit/a6c1c04d4d2339f0094422974ae3f26f8c7c8565)
- ref: main

## linux x86_64 (azure)

- [pystats raw](bm-20231104-azure-x86_64-python-main-3.13.0a1%2B-853b4b5-pystats.json)
- [pystats table](bm-20231104-azure-x86_64-python-main-3.13.0a1%2B-853b4b5-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5.json)

### vs. 3.10.4

- Geometric mean: 1.35x faster \* (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.10.4.md)
- [plot](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.11.0.md)
- [plot](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.12.0.md)
- [plot](bm-20231104-linux-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.10.4.md)
- [plot](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.53%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.11.0.md)
- [plot](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 97.45%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.12.0.md)
- [plot](bm-20231104-pythonperf2-x86_64-python-main-3.13.0a1%2B-853b4b5-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5.json)

### vs. 3.10.4

- Geometric mean: 1.17x faster (HPT: reliability of 100.00%, 1.10x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5-vs-3.10.4.md)
- [plot](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower (HPT: reliability of 99.52%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5-vs-3.11.0.md)
- [plot](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower (HPT: reliability of 76.91%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5-vs-3.12.0.md)
- [plot](bm-20231104-darwin-arm64-python-main-3.13.0a1%2B-853b4b5-vs-3.12.0.png)

