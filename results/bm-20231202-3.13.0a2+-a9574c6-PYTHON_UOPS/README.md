# Results

- fork: python
- version: 3.13.0a2+
- tier 2: True
- commit hash: [a9574c6](https://github.com/python/cpython/commit/a9574c6)
- commit date: 2023-12-02T15:39:43-08:00
- commit merge base: [0229d2a9b1d6ce6daa6a773f92e3754e7dc86d50](https://github.com/python/cpython/commit/0229d2a9b1d6ce6daa6a773f92e3754e7dc86d50)
- ref: a9574c68f04695eecd19

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7073496735)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md)
- [plot](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 98.72%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md)
- [plot](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md)
- [plot](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.07x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md)
- [plot](bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7073496735)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md)
- [plot](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.64%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md)
- [plot](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.12x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md)
- [plot](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.10x slower (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- [table](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md)
- [plot](bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7073496735)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6.json)

### vs. 3.10.4

- Geometric mean: 1.12x faster \* (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md)
- [plot](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 86.81%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md)
- [plot](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md)
- [plot](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md)
- [plot](bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7073496735)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6.json)

### vs. 3.10.4

- Geometric mean: 1.08x faster \* (HPT: reliability of 99.48%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md)
- [plot](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.11x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md)
- [plot](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.10x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md)
- [plot](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.06x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md)
- [plot](bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.png)

