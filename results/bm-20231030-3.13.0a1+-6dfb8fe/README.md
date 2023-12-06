# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [6dfb8fe](https://github.com/python/cpython/commit/6dfb8fe)
- commit date: 2023-10-30T16:06:09+00:00
- commit merge base: [05f2f0ac92afa560315eb66fd6576683c7f69e2d](https://github.com/python/cpython/commit/05f2f0ac92afa560315eb66fd6576683c7f69e2d)
- ref: 6dfb8fe0236718e9afc8

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6707996351)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.md)
- [plot](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster (HPT: reliability of 99.68%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.md)
- [plot](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.88%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.md)
- [plot](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 95.81%, 1.00x slower at 99th %ile)
- [table](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.md)
- [plot](bm-20231030-linux-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6707996351)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.md)
- [plot](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster (HPT: reliability of 98.93%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.md)
- [plot](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower (HPT: reliability of 99.41%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.md)
- [plot](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 99.16%, 1.00x faster at 99th %ile)
- [table](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.md)
- [plot](bm-20231030-pythonperf2-x86_64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6707996351)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.md)
- [plot](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster (HPT: reliability of 86.18%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.md)
- [plot](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.md)
- [plot](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- [table](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.md)
- [plot](bm-20231030-pythonperf1-amd64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6707996351)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.md)
- [plot](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 91.60%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.md)
- [plot](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 60.44%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.md)
- [plot](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 99.69%, 1.00x slower at 99th %ile)
- [table](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.md)
- [plot](bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1%2B-6dfb8fe-vs-base.png)

