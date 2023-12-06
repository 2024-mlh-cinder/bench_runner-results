# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [9c6f64f](https://github.com/faster%2dcpython/cpython/commit/9c6f64f)
- commit date: 2023-11-02T06:49:28+00:00
- commit merge base: [7810b6981ac663b77bc9ee9dc4b1960ec6845ea7](https://github.com/faster%2dcpython/cpython/commit/7810b6981ac663b77bc9ee9dc4b1960ec6845ea7)
- ref: tier_2_exponential_b

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6743564464)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f-vs-3.10.4.md)
- [plot](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 50.62%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f-vs-3.11.0.md)
- [plot](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f-vs-3.12.0.md)
- [plot](bm-20231102-pythonperf2-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-9c6f64f-vs-3.12.0.png)

