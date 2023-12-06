# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: False
- commit hash: [d805312](https://github.com/gvanrossum/cpython/commit/d805312)
- commit date: 2023-10-28T14:06:00-07:00
- commit merge base: [8a158a753c48d166ebceae0687e88ae0c0725c02](https://github.com/gvanrossum/cpython/commit/8a158a753c48d166ebceae0687e88ae0c0725c02)
- ref: mix_tiers

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6679231485)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312.json)

### vs. 3.10.4

- Geometric mean: 1.32x faster (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-3.10.4.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster (HPT: reliability of 98.74%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-3.11.0.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.83%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-3.12.0.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 85.08%, 1.00x slower at 99th %ile)
- [table](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-base.md)
- [plot](bm-20231028-linux-x86_64-gvanrossum-mix_tiers-3.13.0a1%2B-d805312-vs-base.png)

