# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [dabc0d7](https://github.com/python/cpython/commit/dabc0d7)
- commit date: 2023-11-17T15:11:30-08:00
- commit merge base: [da314f7c8dae4f0670306f2ee8b59519a58bf346](https://github.com/python/cpython/commit/da314f7c8dae4f0670306f2ee8b59519a58bf346)
- ref: dabc0d77b21d8cc619a2

## linux x86_64 (azure)

- [pystats raw](bm-20231117-azure-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-pystats.json)
- [pystats table](bm-20231117-azure-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6910571427)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-vs-3.10.4.md)
- [plot](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 99.94%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-vs-3.11.0.md)
- [plot](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.08x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-vs-3.12.0.md)
- [plot](bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1%2B-dabc0d7-vs-3.12.0.png)

