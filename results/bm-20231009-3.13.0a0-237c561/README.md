# Results

- fork: mdboom
- version: 3.13.0a0
- tier 2: False
- commit hash: [237c561](https://github.com/mdboom/cpython/commit/237c561)
- commit date: 2023-10-09T13:50:19-04:00
- commit merge base: [9eb2489266c4c1f115b8f72c0728db737cc8a815](https://github.com/mdboom/cpython/commit/9eb2489266c4c1f115b8f72c0728db737cc8a815)
- ref: collect_tier2_stats

## linux x86_64 (azure)

- [pystats raw](bm-20231009-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-pystats.json)
- [pystats table](bm-20231009-azure-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-pystats.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6460067081)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-vs-3.10.4.md)
- [plot](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-vs-3.11.0.md)
- [plot](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.08x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-vs-3.12.0.md)
- [plot](bm-20231009-linux-x86_64-mdboom-collect_tier2_stats-3.13.0a0-237c561-vs-3.12.0.png)

