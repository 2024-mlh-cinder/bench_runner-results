# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [a077b2f](https://github.com/python/cpython/commit/a077b2f)
- commit date: 2023-11-07T13:40:58+02:00
- commit merge base: [931f4438c92ec0eb2aa894092a91749f1d5bd216](https://github.com/python/cpython/commit/931f4438c92ec0eb2aa894092a91749f1d5bd216)
- ref: a077b2fbb88f5192bb47

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6785253433)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f.json)

### vs. 3.10.4

- Geometric mean: 1.35x faster \* (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-3.10.4.md)
- [plot](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-3.11.0.md)
- [plot](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-3.12.0.md)
- [plot](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 78.76%, 1.00x faster at 99th %ile)
- [table](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-base.md)
- [plot](bm-20231107-linux-x86_64-python-a077b2fbb88f5192bb47-3.13.0a1%2B-a077b2f-vs-base.png)

