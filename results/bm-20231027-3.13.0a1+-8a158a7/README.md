# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [8a158a7](https://github.com/python/cpython/commit/8a158a7)
- commit date: 2023-10-27T18:36:22+00:00
- ref: 8a158a753c48d166ebce

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6679231485)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7-vs-3.10.4.md)
- [plot](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster (HPT: reliability of 99.94%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7-vs-3.11.0.md)
- [plot](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7-vs-3.12.0.md)
- [plot](bm-20231027-linux-x86_64-python-8a158a753c48d166ebce-3.13.0a1%2B-8a158a7-vs-3.12.0.png)

