# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [01e464a](https://github.com/faster%2dcpython/cpython/commit/01e464a)
- commit date: 2023-11-04T19:31:01+00:00
- commit merge base: [931f4438c92ec0eb2aa894092a91749f1d5bd216](https://github.com/faster%2dcpython/cpython/commit/931f4438c92ec0eb2aa894092a91749f1d5bd216)
- ref: optimize_globals_to_

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6788355799)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-3.10.4.md)
- [plot](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.58%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-3.11.0.md)
- [plot](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-3.12.0.md)
- [plot](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- [table](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-base.md)
- [plot](bm-20231104-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-01e464a-vs-base.png)

