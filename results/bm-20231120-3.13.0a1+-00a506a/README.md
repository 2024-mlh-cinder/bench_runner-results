# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [00a506a](https://github.com/mdboom/cpython/commit/00a506a)
- commit date: 2023-11-20T15:16:19-05:00
- commit merge base: [2dbb2e035b968811ddc00317ccf0cadafacffe1c](https://github.com/mdboom/cpython/commit/2dbb2e035b968811ddc00317ccf0cadafacffe1c)
- ref: alternative_workarou

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-3.10.4.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-3.11.0.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 96.92%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-3.12.0.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 68.26%, 1.00x faster at 99th %ile)
- [table](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-base.md)
- [plot](bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-00a506a-vs-base.png)

