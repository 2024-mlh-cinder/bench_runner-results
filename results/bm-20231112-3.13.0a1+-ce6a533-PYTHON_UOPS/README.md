# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [ce6a533](https://github.com/python/cpython/commit/ce6a533)
- commit date: 2023-11-12T01:03:34+01:00
- commit merge base: [21615f77b5a580e83589abae618dbe7c298700e2](https://github.com/python/cpython/commit/21615f77b5a580e83589abae618dbe7c298700e2)
- ref: ce6a533c4bf1afa3775d, main

## linux x86_64 (azure)

- [pystats raw](bm-20231112-azure-x86_64-python-main-3.13.0a1%2B-ce6a533-pystats.json)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6837450031)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.10.4.md)
- [plot](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.87%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.11.0.md)
- [plot](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.12.0.md)
- [plot](bm-20231112-linux-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6837450031)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.10.4.md)
- [plot](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 99.58%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.11.0.md)
- [plot](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.13x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.12.0.md)
- [plot](bm-20231112-pythonperf2-x86_64-python-main-3.13.0a1%2B-ce6a533-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6866608791)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533.json)

### vs. 3.10.4

- Geometric mean: 1.14x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533-vs-3.10.4.md)
- [plot](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 69.52%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533-vs-3.11.0.md)
- [plot](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533-vs-3.12.0.md)
- [plot](bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1%2B-ce6a533-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6837450031)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533.json)

### vs. 3.10.4

- Geometric mean: 1.08x faster (HPT: reliability of 99.82%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533-vs-3.10.4.md)
- [plot](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.10x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533-vs-3.11.0.md)
- [plot](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533-vs-3.12.0.md)
- [plot](bm-20231112-darwin-arm64-python-main-3.13.0a1%2B-ce6a533-vs-3.12.0.png)

