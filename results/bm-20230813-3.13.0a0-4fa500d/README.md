# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [4fa500d](https://github.com/faster%2dcpython/cpython/commit/4fa500d)
- commit date: 2023-08-13T18:48:43+01:00
- commit merge base: [2135bcd3ca9538c6782129f9a5837d62c2036102](https://github.com/faster%2dcpython/cpython/commit/2135bcd3ca9538c6782129f9a5837d62c2036102)
- ref: incremental_gc

## linux x86_64 (azure)

- [pystats raw](bm-20230813-azure-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-pystats.json)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5966258524)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d.json)

### vs. 3.10.4

- Geometric mean: 1.33x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-3.10.4.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 92.57%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-3.11.0.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-3.12.0.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x faster (HPT: reliability of 99.93%, 1.00x faster at 99th %ile)
- [table](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-base.md)
- [plot](bm-20230813-linux-x86_64-faster%252dcpython-incremental_gc-3.13.0a0-4fa500d-vs-base.png)

