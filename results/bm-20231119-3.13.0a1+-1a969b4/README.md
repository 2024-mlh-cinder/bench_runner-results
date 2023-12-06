# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [1a969b4](https://github.com/python/cpython/commit/1a969b4)
- commit date: 2023-11-19T08:21:04+09:00
- commit merge base: [e52cc80f7fc3a560bf3d0053e0821a2db070cdd1](https://github.com/python/cpython/commit/e52cc80f7fc3a560bf3d0053e0821a2db070cdd1)
- ref: 1a969b4f55f92a17bec8

## linux x86_64 (azure)

- [pystats raw](bm-20231119-azure-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-pystats.json)
- [pystats table](bm-20231119-azure-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-pystats.md)

### vs. base

- [pystats diff](bm-20231119-azure-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6917201987)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.10.4.md)
- [plot](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.11.0.md)
- [plot](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.12.0.md)
- [plot](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.12x faster (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- [table](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-base.md)
- [plot](bm-20231119-linux-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6917201987)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.10.4.md)
- [plot](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.96%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.11.0.md)
- [plot](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 71.14%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.12.0.md)
- [plot](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- [table](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-base.md)
- [plot](bm-20231119-pythonperf2-x86_64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6917201987)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.10.4.md)
- [plot](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.11.0.md)
- [plot](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.46%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.12.0.md)
- [plot](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.06x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- [table](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-base.md)
- [plot](bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1%2B-1a969b4-vs-base.png)

