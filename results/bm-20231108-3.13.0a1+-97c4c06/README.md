# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [97c4c06](https://github.com/python/cpython/commit/97c4c06)
- commit date: 2023-11-08T17:20:35-08:00
- commit merge base: [31c90d5838e8d6e4c47d98500a34810ccb33a6d4](https://github.com/python/cpython/commit/31c90d5838e8d6e4c47d98500a34810ccb33a6d4)
- ref: 97c4c06d0d235aad00e5

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6813914394)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06-vs-3.10.4.md)
- [plot](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06-vs-3.11.0.md)
- [plot](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.94%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06-vs-3.12.0.md)
- [plot](bm-20231108-linux-x86_64-python-97c4c06d0d235aad00e5-3.13.0a1%2B-97c4c06-vs-3.12.0.png)

