# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [0ee2d77](https://github.com/python/cpython/commit/0ee2d77)
- commit date: 2023-11-17T14:03:02+09:00
- commit merge base: [8cd70eefc7f3363cfa0d43f34522c3072fa9e160](https://github.com/python/cpython/commit/8cd70eefc7f3363cfa0d43f34522c3072fa9e160)
- ref: 0ee2d77331f2362fcaab

## linux x86_64 (azure)

- [pystats raw](bm-20231117-azure-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-pystats.json)
- [pystats table](bm-20231117-azure-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6905261349)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.10.4.md)
- [plot](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 96.83%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.11.0.md)
- [plot](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.99%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.12.0.md)
- [plot](bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6903465004)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster \* (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.10.4.md)
- [plot](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 88.06%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.11.0.md)
- [plot](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.09x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.12.0.md)
- [plot](bm-20231117-pythonperf2-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1%2B-0ee2d77-vs-3.12.0.png)

