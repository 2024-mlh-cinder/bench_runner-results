# Results

- fork: python
- version: 3.11.0a7
- tier 2: False
- commit hash: [2e49bd0](https://github.com/python/cpython/commit/2e49bd0)
- commit date: 2022-04-05T20:54:03+01:00
- commit merge base: [c1d93b6411f975d67e43942f1a2745a22983c18c](https://github.com/python/cpython/commit/c1d93b6411f975d67e43942f1a2745a22983c18c)
- commit date: 2022-04-05T19:54:03+00:00
- ref: 2e49bd06c5ffab7d1540, main

## linux x86_64 (linux)

- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-91-generic-x86_64-with-glibc2.31
- [raw results](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0.json)

### vs. 3.10.4

- Geometric mean: 1.32x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
- [table](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0-vs-3.10.4.md)
- [plot](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.87%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
- [table](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0-vs-3.11.0.md)
- [plot](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 99.96%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
- new benchmarks: html5lib, thrift
- [table](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0-vs-3.12.0.md)
- [plot](bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/4513535658)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-67-generic-x86_64-with-glibc2.35
- [raw results](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.10.4.md)
- [plot](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.72%, 1.00x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.11.0.md)
- [plot](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.12.0.md)
- [plot](bm-20220405-pythonperf2-x86_64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6961753146)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0.json)

### vs. 3.10.4

- Geometric mean: 1.17x faster (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: dask
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.10.4.md)
- [plot](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower (HPT: reliability of 99.81%, 1.00x slower at 99th %ile)
- missing benchmarks: dask
- [table](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.11.0.md)
- [plot](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower (HPT: reliability of 97.60%, 1.00x faster at 99th %ile)
- missing benchmarks: dask
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.12.0.md)
- [plot](bm-20220405-darwin-arm64-python-2e49bd06c5ffab7d1540-3.11.0a7-2e49bd0-vs-3.12.0.png)

