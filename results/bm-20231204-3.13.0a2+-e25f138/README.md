# Results

- fork: mdboom
- version: 3.13.0a2+
- tier 2: False
- commit hash: [e25f138](https://github.com/mdboom/cpython/commit/e25f138)
- commit date: 2023-12-04T10:30:28-05:00
- commit merge base: [05a370abd6cdfe4b54be60b3b911f3a441026bb2](https://github.com/mdboom/cpython/commit/05a370abd6cdfe4b54be60b3b911f3a441026bb2)
- ref: compact_ints2

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7088929811)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.10.4.md)
- [plot](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.11.0.md)
- [plot](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.12.0.md)
- [plot](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 86.81%, 1.00x faster at 99th %ile)
- missing benchmarks: 🔴 dask
- [table](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-base.md)
- [plot](bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-base.png)

