# Results

- fork: mdboom
- version: 3.13.0a0
- tier 2: False
- commit hash: [3f2d583](https://github.com/mdboom/cpython/commit/3f2d583)
- commit date: 2023-10-04T16:12:22-04:00
- commit merge base: [f7860295b16a402621e209871c8eaeeea16f464e](https://github.com/mdboom/cpython/commit/f7860295b16a402621e209871c8eaeeea16f464e)
- ref: collect_tier2_stats

## linux x86_64 (azure)

- [pystats raw](bm-20231004-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-pystats.json)
- [pystats table](bm-20231004-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-pystats.md)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6411002720)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-vs-3.10.4.md)
- [plot](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 98.30%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-vs-3.11.0.md)
- [plot](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.08x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-vs-3.12.0.md)
- [plot](bm-20231004-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-3f2d583-vs-3.12.0.png)

