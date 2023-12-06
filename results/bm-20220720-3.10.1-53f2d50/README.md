# Results

- fork: mdboom
- version: 3.10.1
- tier 2: False
- commit hash: [53f2d50](https://github.com/mdboom/cpython/commit/53f2d50)
- commit date: 2022-07-20T21:48:30+08:00
- ref: RegCPython

## linux x86_64 (linux)

- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50.json)

### vs. 3.10.4

- Geometric mean: 1.06x faster \* (HPT: reliability of 100.00%, 1.03x faster at 99th %ile)
- missing benchmarks: asyncio_tcp_ssl, asyncio_websockets, comprehensions, coverage, dask, mypy2, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: mypy
- [table](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50-vs-3.10.4.md)
- [plot](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.18x slower \* (HPT: reliability of 100.00%, 1.13x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, coverage, dask, mypy2, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: mypy
- [table](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50-vs-3.11.0.md)
- [plot](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.20x slower \* (HPT: reliability of 100.00%, 1.13x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, coverage, dask, mypy2, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, mypy, pylint, thrift
- [table](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50-vs-3.12.0.md)
- [plot](bm-20220720-linux-x86_64-mdboom-RegCPython-3.10.1-53f2d50-vs-3.12.0.png)

