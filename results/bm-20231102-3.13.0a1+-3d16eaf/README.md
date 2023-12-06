# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [3d16eaf](https://github.com/mdboom/cpython/commit/3d16eaf)
- commit date: 2023-11-02T14:21:11-04:00
- commit merge base: [0887b9ce8b5b4f9ecdef014b9329da78a46c9f42](https://github.com/mdboom/cpython/commit/0887b9ce8b5b4f9ecdef014b9329da78a46c9f42)
- ref: collect_tier2_stats

## linux x86_64 (azure)

- [pystats raw](bm-20231102-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-pystats.json)
- [pystats table](bm-20231102-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6736700689)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.19x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-vs-3.10.4.md)
- [plot](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 88.93%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-vs-3.11.0.md)
- [plot](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.93%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-vs-3.12.0.md)
- [plot](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-3d16eaf-vs-3.12.0.png)

