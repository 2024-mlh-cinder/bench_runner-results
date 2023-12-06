# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [b635f8d](https://github.com/mdboom/cpython/commit/b635f8d)
- commit date: 2023-11-06T20:04:33-05:00
- commit merge base: [a077b2fbb88f5192bb47e514334f760bf08d0295](https://github.com/mdboom/cpython/commit/a077b2fbb88f5192bb47e514334f760bf08d0295)
- ref: disable_optimize_gcc

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6785253433)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-3.10.4.md)
- [plot](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.99%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-3.11.0.md)
- [plot](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-3.12.0.md)
- [plot](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.11x slower (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- [table](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-base.md)
- [plot](bm-20231106-linux-x86_64-mdboom-disable_optimize_gcc-3.13.0a1%2B-b635f8d-vs-base.png)

