# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [4f04172](https://github.com/python/cpython/commit/4f04172)
- commit date: 2023-11-14T12:51:00+00:00
- commit merge base: [f44d6ff6e0c9eeb0bb246a3dd8f99d40b7050054](https://github.com/python/cpython/commit/f44d6ff6e0c9eeb0bb246a3dd8f99d40b7050054)
- ref: 4f04172c9287c507f142

## linux x86_64 (azure)

- [pystats raw](bm-20231114-azure-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-pystats.json)
- [pystats table](bm-20231114-azure-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6864228122)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-vs-3.10.4.md)
- [plot](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.61%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-vs-3.11.0.md)
- [plot](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-vs-3.12.0.md)
- [plot](bm-20231114-linux-x86_64-python-4f04172c9287c507f142-3.13.0a1%2B-4f04172-vs-3.12.0.png)

