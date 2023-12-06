# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [0e83d94](https://github.com/python/cpython/commit/0e83d94)
- commit date: 2023-11-07T11:23:57-08:00
- commit merge base: [2f9cb7e095370e38bde58c79c8a8ea7705eefdc2](https://github.com/python/cpython/commit/2f9cb7e095370e38bde58c79c8a8ea7705eefdc2)
- ref: 0e83d941bea921380ce4

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6804530900)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94-vs-3.10.4.md)
- [plot](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94-vs-3.11.0.md)
- [plot](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.82%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94-vs-3.12.0.md)
- [plot](bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1%2B-0e83d94-vs-3.12.0.png)

