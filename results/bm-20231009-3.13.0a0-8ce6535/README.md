# Results

- fork: mdboom
- version: 3.13.0a0
- tier 2: False
- commit hash: [8ce6535](https://github.com/mdboom/cpython/commit/8ce6535)
- commit date: 2023-10-09T09:52:21-04:00
- commit merge base: [9eb2489266c4c1f115b8f72c0728db737cc8a815](https://github.com/mdboom/cpython/commit/9eb2489266c4c1f115b8f72c0728db737cc8a815)
- ref: count_tier2_miss_opc

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6458126808)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535-vs-3.10.4.md)
- [plot](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 85.15%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535-vs-3.11.0.md)
- [plot](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 94.66%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535-vs-3.12.0.md)
- [plot](bm-20231009-linux-x86_64-mdboom-count_tier2_miss_opc-3.13.0a0-8ce6535-vs-3.12.0.png)

