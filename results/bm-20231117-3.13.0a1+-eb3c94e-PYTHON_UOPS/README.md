# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [eb3c94e](https://github.com/python/cpython/commit/eb3c94e)
- commit date: 2023-11-17T20:58:13-08:00
- commit merge base: [43b1c33204d125e256f7a0c3086ba547b71a105e](https://github.com/python/cpython/commit/43b1c33204d125e256f7a0c3086ba547b71a105e)
- ref: eb3c94ea669561a0dfac

## linux x86_64 (azure)

- [pystats raw](bm-20231117-azure-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-pystats.json)
- [pystats table](bm-20231117-azure-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6922482470)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-vs-3.10.4.md)
- [plot](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 98.67%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-vs-3.11.0.md)
- [plot](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-vs-3.12.0.md)
- [plot](bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1%2B-eb3c94e-vs-3.12.0.png)

