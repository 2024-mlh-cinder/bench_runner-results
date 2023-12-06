# Results

- fork: mdboom
- version: 3.13.0a0
- tier 2: False
- commit hash: [9e1c90d](https://github.com/mdboom/cpython/commit/9e1c90d)
- commit date: 2023-10-03T12:01:22-04:00
- commit merge base: [ecd813f054e0dee890d484b8210e202175abd632](https://github.com/mdboom/cpython/commit/ecd813f054e0dee890d484b8210e202175abd632)
- ref: collect_tier2_stats

## linux x86_64 (azure)

- [pystats raw](bm-20231003-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-pystats.json)
- [pystats table](bm-20231003-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-pystats.md)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6395484895)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-vs-3.10.4.md)
- [plot](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 91.21%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-vs-3.11.0.md)
- [plot](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-vs-3.12.0.md)
- [plot](bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d-vs-3.12.0.png)

