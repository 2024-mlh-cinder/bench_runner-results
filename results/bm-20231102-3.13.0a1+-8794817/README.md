# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [8794817](https://github.com/mdboom/cpython/commit/8794817)
- commit date: 2023-11-02T18:18:55-04:00
- commit merge base: [9f33ede12710c454643c394421f52d209247272c](https://github.com/mdboom/cpython/commit/9f33ede12710c454643c394421f52d209247272c)
- ref: collect_tier2_stats

## linux x86_64 (azure)

- [pystats raw](bm-20231102-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-pystats.json)
- [pystats table](bm-20231102-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6746098903)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.20x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-vs-3.10.4.md)
- [plot](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 82.40%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-vs-3.11.0.md)
- [plot](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.78%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-vs-3.12.0.md)
- [plot](bm-20231102-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a1%2B-8794817-vs-3.12.0.png)

