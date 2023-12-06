# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [8deb8bc](https://github.com/python/cpython/commit/8deb8bc)
- commit date: 2023-11-20T11:25:32-08:00
- commit merge base: [c4c63211e83aa50927f3f1e57eacfaf4952ed228](https://github.com/python/cpython/commit/c4c63211e83aa50927f3f1e57eacfaf4952ed228)
- ref: 8deb8bc2e5af0e229df8

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.md)
- [plot](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.md)
- [plot](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.md)
- [plot](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 99.64%, 1.00x slower at 99th %ile)
- [table](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.md)
- [plot](bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.98%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 86.55%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 50.08%, 1.00x faster at 99th %ile)
- [table](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.md)
- [plot](bm-20231120-pythonperf2-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.08x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 98.42%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- [table](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.md)
- [plot](bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc.json)

### vs. 3.10.4

- Geometric mean: 1.17x faster (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.md)
- [plot](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower (HPT: reliability of 99.47%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.md)
- [plot](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower (HPT: reliability of 97.82%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.md)
- [plot](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 74.44%, 1.00x faster at 99th %ile)
- [table](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.md)
- [plot](bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1%2B-8deb8bc-vs-base.png)

