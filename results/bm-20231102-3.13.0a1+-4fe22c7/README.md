# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [4fe22c7](https://github.com/python/cpython/commit/4fe22c7)
- commit date: 2023-11-02T14:29:05+01:00
- commit merge base: [6a0d7b43df12ab4426badd09d2796e66838129ac](https://github.com/python/cpython/commit/6a0d7b43df12ab4426badd09d2796e66838129ac)
- ref: 4fe22c73770fe86b01ef

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6735040445)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7-vs-3.10.4.md)
- [plot](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster (HPT: reliability of 99.87%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7-vs-3.11.0.md)
- [plot](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower (HPT: reliability of 62.67%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7-vs-3.12.0.md)
- [plot](bm-20231102-pythonperf2-x86_64-python-4fe22c73770fe86b01ef-3.13.0a1%2B-4fe22c7-vs-3.12.0.png)

