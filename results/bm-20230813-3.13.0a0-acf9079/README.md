# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [acf9079](https://github.com/faster%2dcpython/cpython/commit/acf9079)
- commit date: 2023-08-13T03:33:12+01:00
- commit merge base: [2ac103c346ffe9d0e4c146402ce215c5ce6c1ef2](https://github.com/faster%2dcpython/cpython/commit/2ac103c346ffe9d0e4c146402ce215c5ce6c1ef2)
- ref: incremental_gc

## linux x86_64 (azure)

- [pystats raw](bm-20230813-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-pystats.json)
- [pystats table](bm-20230813-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-pystats.md)

### vs. base

- [pystats diff](bm-20230813-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5941246588)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-3.10.4.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 92.11%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-3.11.0.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.99%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-3.12.0.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x faster (HPT: reliability of 95.66%, 1.00x faster at 99th %ile)
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-base.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-acf9079-vs-base.png)

