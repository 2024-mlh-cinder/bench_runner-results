# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [30e5f4b](https://github.com/faster%2dcpython/cpython/commit/30e5f4b)
- commit date: 2023-11-04T13:45:34+00:00
- commit merge base: [931f4438c92ec0eb2aa894092a91749f1d5bd216](https://github.com/faster%2dcpython/cpython/commit/931f4438c92ec0eb2aa894092a91749f1d5bd216)
- ref: optimize_globals_to_

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6784496714)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-3.10.4.md)
- [plot](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.74%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-3.11.0.md)
- [plot](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 77.85%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-3.12.0.md)
- [plot](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 51.09%, 1.00x slower at 99th %ile)
- [table](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-base.md)
- [plot](bm-20231104-pythonperf2-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-30e5f4b-vs-base.png)

