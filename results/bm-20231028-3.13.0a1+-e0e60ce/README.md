# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: False
- commit hash: [e0e60ce](https://github.com/gvanrossum/cpython/commit/e0e60ce)
- commit date: 2023-10-28T17:04:55-07:00
- commit merge base: [8a158a753c48d166ebceae0687e88ae0c0725c02](https://github.com/gvanrossum/cpython/commit/8a158a753c48d166ebceae0687e88ae0c0725c02)
- ref: mix_tiers

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6679947095)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-3.10.4.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower (HPT: reliability of 98.21%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-3.11.0.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-3.12.0.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.07x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-base.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-e0e60ce-vs-base.png)

