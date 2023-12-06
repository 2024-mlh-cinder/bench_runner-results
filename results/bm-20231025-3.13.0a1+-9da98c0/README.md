# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [9da98c0](https://github.com/python/cpython/commit/9da98c0)
- commit date: 2023-10-25T13:50:16+03:00
- ref: 9da98c0d9a7cc55c67fb

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6654939507)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0-vs-3.10.4.md)
- [plot](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster (HPT: reliability of 99.88%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0-vs-3.11.0.md)
- [plot](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.84%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0-vs-3.12.0.md)
- [plot](bm-20231025-linux-x86_64-python-9da98c0d9a7cc55c67fb-3.13.0a1%2B-9da98c0-vs-3.12.0.png)

