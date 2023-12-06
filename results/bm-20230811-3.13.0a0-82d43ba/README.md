# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [82d43ba](https://github.com/faster%2dcpython/cpython/commit/82d43ba)
- commit date: 2023-08-11T11:24:48+01:00
- commit merge base: [2ac103c346ffe9d0e4c146402ce215c5ce6c1ef2](https://github.com/faster%2dcpython/cpython/commit/2ac103c346ffe9d0e4c146402ce215c5ce6c1ef2)
- ref: incremental_gc

## linux x86_64 (azure)

- [pystats raw](bm-20230811-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-pystats.json)
- [pystats table](bm-20230811-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-pystats.md)

### vs. base

- [pystats diff](bm-20230811-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-pystats-vs-base.md)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5879282122)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-3.10.4.md)
- [plot](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 70.65%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-3.11.0.md)
- [plot](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 98.24%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-3.12.0.md)
- [plot](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 88.84%, 1.00x faster at 99th %ile)
- [table](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-base.md)
- [plot](bm-20230811-pythonperf2-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-82d43ba-vs-base.png)

