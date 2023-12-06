# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [bf453f8](https://github.com/faster%2dcpython/cpython/commit/bf453f8)
- commit date: 2023-11-02T14:05:18+00:00
- commit merge base: [2bc01cc0c72a3d91bdcce09886efa987a90396d9](https://github.com/faster%2dcpython/cpython/commit/2bc01cc0c72a3d91bdcce09886efa987a90396d9)
- ref: tier_2_exponential_b

## linux x86_64 (azure)

- [pystats raw](bm-20231102-azure-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-pystats.json)
- [pystats table](bm-20231102-azure-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-pystats.md)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6747758896)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-vs-3.10.4.md)
- [plot](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 55.57%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-vs-3.11.0.md)
- [plot](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-vs-3.12.0.md)
- [plot](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bf453f8-vs-3.12.0.png)

