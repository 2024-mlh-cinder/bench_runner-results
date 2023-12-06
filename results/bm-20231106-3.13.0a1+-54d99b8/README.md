# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [54d99b8](https://github.com/mdboom/cpython/commit/54d99b8)
- commit date: 2023-11-06T03:57:48-05:00
- commit merge base: [4ebf2fae9664a4042511](https://github.com/mdboom/cpython/commit/4ebf2fae9664a4042511)
- ref: optimize_off

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6774965225)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-3.10.4.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.08x faster \* (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-3.11.0.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.40%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-3.12.0.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.06x faster \* (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- [table](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-base.md)
- [plot](bm-20231106-pythonperf1-amd64-mdboom-optimize_off-3.13.0a1%2B-54d99b8-vs-base.png)

