# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [931f443](https://github.com/python/cpython/commit/931f443)
- commit date: 2023-11-07T09:42:39+00:00
- commit merge base: [13405ecffda6c66d6a5cf2a22dff892c108c69db](https://github.com/python/cpython/commit/13405ecffda6c66d6a5cf2a22dff892c108c69db)
- ref: 931f4438c92ec0eb2aa8

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6788355799)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.10.4.md)
- [plot](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.11.0.md)
- [plot](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.12.0.md)
- [plot](bm-20231107-linux-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6784496714)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.10.4.md)
- [plot](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.97%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.11.0.md)
- [plot](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 81.48%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.12.0.md)
- [plot](bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1%2B-931f443-vs-3.12.0.png)

