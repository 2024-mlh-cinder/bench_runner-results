# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: True
- commit hash: [7bb54b5](https://github.com/brandtbucher/cpython/commit/7bb54b5)
- commit date: 2023-11-20T10:57:03-08:00
- commit merge base: [c4c63211e83aa50927f3f1e57eacfaf4952ed228](https://github.com/brandtbucher/cpython/commit/c4c63211e83aa50927f3f1e57eacfaf4952ed228)
- ref: justin

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6940282382)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.md)
- [plot](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 62.55%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.md)
- [plot](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 83.43%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.md)
- [plot](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.08x faster (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- [table](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-base.md)
- [plot](bm-20231120-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6940282382)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 86.22%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.10x faster (HPT: reliability of 100.00%, 1.04x faster at 99th %ile)
- [table](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-base.md)
- [plot](bm-20231120-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6940282382)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 88.17%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6940282382)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5.json)

### vs. 3.10.4

- Geometric mean: 1.14x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.md)
- [plot](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower (HPT: reliability of 99.97%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.md)
- [plot](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.md)
- [plot](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- [table](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-base.md)
- [plot](bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1%2B-7bb54b5-vs-base.png)

