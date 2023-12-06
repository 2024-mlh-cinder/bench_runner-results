# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [2dbb2e0](https://github.com/python/cpython/commit/2dbb2e0)
- commit date: 2023-11-17T07:32:50-08:00
- commit merge base: [7c50800241997f93647a57354c052de2cec25d04](https://github.com/python/cpython/commit/7c50800241997f93647a57354c052de2cec25d04)
- ref: 2dbb2e035b968811ddc0

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6907179971)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster \* (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-3.10.4.md)
- [plot](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 79.66%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-3.11.0.md)
- [plot](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.96%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-3.12.0.md)
- [plot](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-base.md)
- [plot](bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1%2B-2dbb2e0-vs-base.png)

