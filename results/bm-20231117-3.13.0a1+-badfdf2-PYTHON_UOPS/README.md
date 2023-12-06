# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: True
- commit hash: [badfdf2](https://github.com/mdboom/cpython/commit/badfdf2)
- commit date: 2023-11-17T11:45:12-05:00
- commit merge base: [2dbb2e035b968811ddc00317ccf0cadafacffe1c](https://github.com/mdboom/cpython/commit/2dbb2e035b968811ddc00317ccf0cadafacffe1c)
- ref: alternative_workarou

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6906732103)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2.json)

### vs. 3.10.4

- Geometric mean: 1.13x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-3.10.4.md)
- [plot](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 55.27%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-3.11.0.md)
- [plot](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-3.12.0.md)
- [plot](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 99.99%, 1.00x slower at 99th %ile)
- [table](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-base.md)
- [plot](bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1%2B-badfdf2-vs-base.png)

