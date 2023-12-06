# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [eadfe93](https://github.com/mdboom/cpython/commit/eadfe93)
- commit date: 2023-11-06T06:27:55-05:00
- commit merge base: [9f33ede12710c454643c394421f52d209247272c](https://github.com/mdboom/cpython/commit/9f33ede12710c454643c394421f52d209247272c)
- ref: optimize_off

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6789076662)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93.json)

### vs. 3.10.4

- Geometric mean: 1.26x slower \* (HPT: reliability of 100.00%, 1.16x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93-vs-3.10.4.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.41x slower \* (HPT: reliability of 100.00%, 1.26x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93-vs-3.11.0.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.49x slower \* (HPT: reliability of 100.00%, 1.34x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93-vs-3.12.0.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-eadfe93-vs-3.12.0.png)

