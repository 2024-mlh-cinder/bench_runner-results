# Results

- fork: iritkatriel
- version: 3.13.0a1+
- tier 2: False
- commit hash: [03335e6](https://github.com/iritkatriel/cpython/commit/03335e6)
- commit date: 2023-10-26T17:16:22+01:00
- commit merge base: [a0c414c35d0dc0d44a885fda448652e23de2482c](https://github.com/iritkatriel/cpython/commit/a0c414c35d0dc0d44a885fda448652e23de2482c)
- ref: gen_close

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6656910155)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-3.10.4.md)
- [plot](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster (HPT: reliability of 99.98%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-3.11.0.md)
- [plot](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-3.12.0.md)
- [plot](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 89.85%, 1.00x faster at 99th %ile)
- [table](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-base.md)
- [plot](bm-20231026-linux-x86_64-iritkatriel-gen_close-3.13.0a1%2B-03335e6-vs-base.png)

