# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [a519b87](https://github.com/python/cpython/commit/a519b87)
- commit date: 2023-11-14T15:30:33+00:00
- commit merge base: [b11c443bb2ebfdd009e43ff208fa6324b658d15d](https://github.com/python/cpython/commit/b11c443bb2ebfdd009e43ff208fa6324b658d15d)
- ref: a519b87958da0b340cae

## linux x86_64 (azure)

- [pystats raw](bm-20231114-azure-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-pystats.json)
- [pystats table](bm-20231114-azure-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6865945502)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-vs-3.10.4.md)
- [plot](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.82%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-vs-3.11.0.md)
- [plot](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-vs-3.12.0.md)
- [plot](bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1%2B-a519b87-vs-3.12.0.png)

