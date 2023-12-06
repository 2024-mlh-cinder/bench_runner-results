# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [a0c414c](https://github.com/python/cpython/commit/a0c414c)
- commit date: 2023-10-26T16:30:18+01:00
- ref: a0c414c35d0dc0d44a88

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6656910155)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c-vs-3.10.4.md)
- [plot](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster (HPT: reliability of 99.91%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c-vs-3.11.0.md)
- [plot](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.71%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c-vs-3.12.0.md)
- [plot](bm-20231026-linux-x86_64-python-a0c414c35d0dc0d44a88-3.13.0a1%2B-a0c414c-vs-3.12.0.png)

