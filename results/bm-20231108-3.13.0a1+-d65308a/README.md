# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: False
- commit hash: [d65308a](https://github.com/brandtbucher/cpython/commit/d65308a)
- commit date: 2023-11-08T12:32:44-08:00
- commit merge base: [0e83d941bea921380ce4a1494121f3ec30ae652e](https://github.com/brandtbucher/cpython/commit/0e83d941bea921380ce4a1494121f3ec30ae652e)
- ref: justin

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6804530900)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-3.10.4.md)
- [plot](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 77.85%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-3.11.0.md)
- [plot](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 82.70%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-3.12.0.md)
- [plot](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-base.md)
- [plot](bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-d65308a-vs-base.png)

