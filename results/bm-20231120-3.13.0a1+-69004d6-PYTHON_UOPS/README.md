# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: True
- commit hash: [69004d6](https://github.com/mdboom/cpython/commit/69004d6)
- commit date: 2023-11-20T18:46:36-05:00
- commit merge base: [8deb8bc2e5af0e229df87002ee8e0b0c1383f572](https://github.com/mdboom/cpython/commit/8deb8bc2e5af0e229df87002ee8e0b0c1383f572)
- ref: pogo2

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6937180609)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster \* (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.md)
- [plot](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.08x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.md)
- [plot](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.11x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.md)
- [plot](bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6937180609)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 98.86%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.13x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6937180609)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6.json)

### vs. 3.10.4

- Geometric mean: 1.14x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 69.23%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6937180609)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6.json)

### vs. 3.10.4

- Geometric mean: 1.08x faster (HPT: reliability of 99.88%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.md)
- [plot](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.10x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.md)
- [plot](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.md)
- [plot](bm-20231120-darwin-arm64-mdboom-pogo2-3.13.0a1%2B-69004d6-vs-3.12.0.png)

