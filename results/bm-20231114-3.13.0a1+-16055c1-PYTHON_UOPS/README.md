# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [16055c1](https://github.com/python/cpython/commit/16055c1)
- commit date: 2023-11-14T11:29:49+02:00
- commit merge base: [95365625f4aa8615c94fbfa10f6a0264ca3054db](https://github.com/python/cpython/commit/95365625f4aa8615c94fbfa10f6a0264ca3054db)
- ref: 16055c160412544e2a49

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6863448890)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1-vs-3.10.4.md)
- [plot](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.88%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1-vs-3.11.0.md)
- [plot](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1-vs-3.12.0.md)
- [plot](bm-20231114-linux-x86_64-python-16055c160412544e2a49-3.13.0a1%2B-16055c1-vs-3.12.0.png)

