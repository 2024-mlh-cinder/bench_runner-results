# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: False
- commit hash: [ab9b54e](https://github.com/gvanrossum/cpython/commit/ab9b54e)
- commit date: 2023-10-30T11:10:54-07:00
- commit merge base: [c19561b9ca2c8f5ed55456174acf768feec072f1](https://github.com/gvanrossum/cpython/commit/c19561b9ca2c8f5ed55456174acf768feec072f1)
- ref: uops_forever

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6696987885)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-3.10.4.md)
- [plot](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower (HPT: reliability of 99.47%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-3.11.0.md)
- [plot](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-3.12.0.md)
- [plot](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.06x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-base.md)
- [plot](bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1%2B-ab9b54e-vs-base.png)

