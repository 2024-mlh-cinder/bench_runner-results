# Results

- fork: python
- version: 3.13.0a2+
- tier 2: False
- commit hash: [3faf8e5](https://github.com/python/cpython/commit/3faf8e5)
- commit date: 2023-11-25T15:40:19-08:00
- commit merge base: [97f8f28b3e50196f6713faceccc2e15039117470](https://github.com/python/cpython/commit/97f8f28b3e50196f6713faceccc2e15039117470)
- ref: 3faf8e586d36e73faba1

## linux x86_64 (azure)

- [pystats raw](bm-20231125-azure-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-pystats.json)
- [pystats table](bm-20231125-azure-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-pystats.md)

### vs. base

- [pystats diff](bm-20231125-azure-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6992284744)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.md)
- [plot](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.97%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.md)
- [plot](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.md)
- [plot](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- [table](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.md)
- [plot](bm-20231125-linux-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6992284744)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.md)
- [plot](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.98%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.md)
- [plot](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 59.31%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.md)
- [plot](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.10x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- [table](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.md)
- [plot](bm-20231125-pythonperf2-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6992284744)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5.json)

### vs. 3.10.4

- Geometric mean: 1.13x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.md)
- [plot](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.52%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.md)
- [plot](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.md)
- [plot](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- [table](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.md)
- [plot](bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6992284744)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.md)
- [plot](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower (HPT: reliability of 99.99%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.md)
- [plot](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower (HPT: reliability of 99.99%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.md)
- [plot](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.06x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- [table](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.md)
- [plot](bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-vs-base.png)

