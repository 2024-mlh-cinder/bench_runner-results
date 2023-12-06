# Results

- fork: mdboom
- version: 3.12.0a4
- tier 2: False
- commit hash: [0fd3163](https://github.com/mdboom/cpython/commit/0fd3163)
- commit date: 2023-05-31T00:05:31-04:00
- commit merge base: [3d5d3f7af6498effbc60a3db1d2b5f41ae6c0a75](https://github.com/mdboom/cpython/commit/3d5d3f7af6498effbc60a3db1d2b5f41ae6c0a75)
- ref: match_nogil_gc

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5136355489)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163.json)

### vs. 3.10.4

- Geometric mean: 1.37x faster \* (HPT: reliability of 100.00%, 1.32x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, flaskblogging, gunicorn, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- [table](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-3.10.4.md)
- [plot](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.10x faster \* (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, flaskblogging, gunicorn, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- [table](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-3.11.0.md)
- [plot](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- new benchmarks: djangocms, genshi_text, genshi_xml, html5lib, thrift
- [table](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-3.12.0.md)
- [plot](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x faster \* (HPT: reliability of 99.54%, 1.00x faster at 99th %ile)
- new benchmarks: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-base.md)
- [plot](bm-20230531-linux-x86_64-mdboom-match_nogil_gc-3.12.0a4-0fd3163-vs-base.png)

