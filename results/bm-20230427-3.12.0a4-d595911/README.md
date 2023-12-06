# Results

- fork: mdboom
- version: 3.12.0a4
- tier 2: False
- commit hash: [d595911](https://github.com/mdboom/cpython/commit/d595911)
- commit date: 2023-04-27T14:06:49-07:00
- ref: nogil_d595911

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5191112544)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, coverage, dask, django_template, djangocms, docutils, dulwich_log, flaskblogging, gunicorn, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift, tornado_http
- [table](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.10.4.md)
- [plot](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage, dask, django_template, djangocms, docutils, dulwich_log, flaskblogging, gunicorn, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift, tornado_http
- [table](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.11.0.md)
- [plot](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage, dask, django_template, docutils, dulwich_log, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- new benchmarks: genshi_text, genshi_xml, html5lib
- [table](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.12.0.md)
- [plot](bm-20230427-linux-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5190752460)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-67-generic-x86_64-with-glibc2.35
- [raw results](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911.json)

### vs. 3.10.4

- Geometric mean: 1.18x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, dask, flaskblogging, gunicorn, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- [table](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.10.4.md)
- [plot](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.90%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, dask, flaskblogging, gunicorn, pylint, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- [table](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.11.0.md)
- [plot](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.09x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, dask, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, tornado_http
- new benchmarks: genshi_text, genshi_xml, html5lib, thrift
- [table](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.12.0.md)
- [plot](bm-20230427-pythonperf2-x86_64-mdboom-nogil_d595911-3.12.0a4-d595911-vs-3.12.0.png)

