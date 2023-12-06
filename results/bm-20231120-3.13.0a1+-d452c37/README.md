# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [d452c37](https://github.com/mdboom/cpython/commit/d452c37)
- commit date: 2023-11-20T17:37:26-05:00
- commit merge base: [8deb8bc2e5af0e229df87002ee8e0b0c1383f572](https://github.com/mdboom/cpython/commit/8deb8bc2e5af0e229df87002ee8e0b0c1383f572)
- ref: alternative_workarou

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-88-generic-x86_64-with-glibc2.35
- [raw results](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.84%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 98.49%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-base.md)
- [plot](bm-20231120-pythonperf2-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.10.4.md)
- [plot](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower (HPT: reliability of 99.79%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.11.0.md)
- [plot](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower (HPT: reliability of 98.71%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.12.0.md)
- [plot](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 99.99%, 1.00x slower at 99th %ile)
- [table](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-base.md)
- [plot](bm-20231120-darwin-arm64-mdboom-alternative_workarou-3.13.0a1%2B-d452c37-vs-base.png)

