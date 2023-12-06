# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: False
- commit hash: [7a7e995](https://github.com/brandtbucher/cpython/commit/7a7e995)
- commit date: 2023-11-15T15:34:27-08:00
- commit merge base: [7e2308aaa29419eadeef3a349c7c4d78e2cbc989](https://github.com/brandtbucher/cpython/commit/7e2308aaa29419eadeef3a349c7c4d78e2cbc989)
- ref: justin

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6894928352)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.10.4.md)
- [plot](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 69.95%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.11.0.md)
- [plot](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 70.75%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.12.0.md)
- [plot](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-base.md)
- [plot](bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6894928352)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.10.4.md)
- [plot](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.08x faster \* (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.11.0.md)
- [plot](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.89%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.12.0.md)
- [plot](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 75.71%, 1.00x slower at 99th %ile)
- [table](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-base.md)
- [plot](bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6894928352)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995.json)

### vs. 3.10.4

- Geometric mean: 1.12x faster (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.10.4.md)
- [plot](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.11.0.md)
- [plot](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.12.0.md)
- [plot](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-base.md)
- [plot](bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7a7e995-vs-base.png)

