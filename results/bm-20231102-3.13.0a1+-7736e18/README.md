# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [7736e18](https://github.com/faster%2dcpython/cpython/commit/7736e18)
- commit date: 2023-11-02T09:00:28+00:00
- commit merge base: [7810b6981ac663b77bc9ee9dc4b1960ec6845ea7](https://github.com/faster%2dcpython/cpython/commit/7810b6981ac663b77bc9ee9dc4b1960ec6845ea7)
- ref: tier_2_exponential_b

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6744730779)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.20x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-3.10.4.md)
- [plot](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 89.29%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-3.11.0.md)
- [plot](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.55%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-3.12.0.md)
- [plot](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-base.md)
- [plot](bm-20231102-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-7736e18-vs-base.png)

