# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [bff925c](https://github.com/faster%2dcpython/cpython/commit/bff925c)
- commit date: 2023-11-05T04:03:22+00:00
- commit merge base: [11e83488c5a4a6e75a4f363a2e1a45574fd53573](https://github.com/faster%2dcpython/cpython/commit/11e83488c5a4a6e75a4f363a2e1a45574fd53573)
- ref: tier_2_exponential_b

## linux x86_64 (azure)

- [pystats raw](bm-20231105-azure-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-pystats.json)
- [pystats table](bm-20231105-azure-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6796654480)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-vs-3.10.4.md)
- [plot](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 94.94%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-vs-3.11.0.md)
- [plot](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.98%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-vs-3.12.0.md)
- [plot](bm-20231105-linux-x86_64-faster%252dcpython-tier_2_exponential_b-3.13.0a1%2B-bff925c-vs-3.12.0.png)

