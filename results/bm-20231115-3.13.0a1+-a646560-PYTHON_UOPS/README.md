# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [a646560](https://github.com/python/cpython/commit/a646560)
- commit date: 2023-11-15T23:53:38+00:00
- commit merge base: [7218bac8c84115a8e9a18a4a8f3146235068facb](https://github.com/python/cpython/commit/7218bac8c84115a8e9a18a4a8f3146235068facb)
- ref: a6465605c1417792ec04

## linux x86_64 (azure)

- [pystats raw](bm-20231115-azure-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-pystats.json)
- [pystats table](bm-20231115-azure-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6886653372)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-vs-3.10.4.md)
- [plot](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 94.56%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-vs-3.11.0.md)
- [plot](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.95%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-vs-3.12.0.md)
- [plot](bm-20231115-linux-x86_64-python-a6465605c1417792ec04-3.13.0a1%2B-a646560-vs-3.12.0.png)

