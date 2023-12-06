# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [bbb758f](https://github.com/mdboom/cpython/commit/bbb758f)
- commit date: 2023-10-31T10:29:32-04:00
- commit merge base: [6dfb8fe0236718e9afc8136ff2b58dcfbc182022](https://github.com/mdboom/cpython/commit/6dfb8fe0236718e9afc8136ff2b58dcfbc182022)
- ref: measure_biased_ref_c

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6711280263)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-3.10.4.md)
- [plot](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-3.11.0.md)
- [plot](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.08x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-3.12.0.md)
- [plot](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x slower \* (HPT: reliability of 100.00%, 1.06x slower at 99th %ile)
- [table](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-base.md)
- [plot](bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1%2B-bbb758f-vs-base.png)

