# Results

- fork: python
- version: 3.13.0a2+
- tier 2: False
- commit hash: [48dfd74](https://github.com/python/cpython/commit/48dfd74)
- commit date: 2023-11-28T08:45:03-07:00
- commit merge base: [3fdf7ae3d1a08894e53c263945fba67fe62ac05b](https://github.com/python/cpython/commit/3fdf7ae3d1a08894e53c263945fba67fe62ac05b)
- ref: 48dfd74a9db9d4aa9c6f

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7036950895)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74.json)

### vs. 3.10.4

- Geometric mean: 1.32x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.10.4.md)
- [plot](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.11.0.md)
- [plot](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.12.0.md)
- [plot](bm-20231128-linux-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7036950895)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.10.4.md)
- [plot](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.95%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.11.0.md)
- [plot](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 78.78%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.12.0.md)
- [plot](bm-20231128-pythonperf2-x86_64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7036950895)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74.json)

### vs. 3.10.4

- Geometric mean: 1.14x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.10.4.md)
- [plot](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.11.0.md)
- [plot](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.12.0.md)
- [plot](bm-20231128-darwin-arm64-python-48dfd74a9db9d4aa9c6f-3.13.0a2%2B-48dfd74-vs-3.12.0.png)

