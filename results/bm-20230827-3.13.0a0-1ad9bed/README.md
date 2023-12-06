# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [1ad9bed](https://github.com/faster%2dcpython/cpython/commit/1ad9bed)
- commit date: 2023-08-27T23:38:58+01:00
- commit merge base: [2928e5dc6512e4206c616cd33e0bcc3288abf6ed](https://github.com/faster%2dcpython/cpython/commit/2928e5dc6512e4206c616cd33e0bcc3288abf6ed)
- ref: no_deep_freeze_3

## linux x86_64 (azure)

- [pystats raw](bm-20230827-azure-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-pystats.json)
- [pystats table](bm-20230827-azure-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-pystats.md)

### vs. base

- [pystats diff](bm-20230827-azure-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6035390507)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-3.10.4.md)
- [plot](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 94.12%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-3.11.0.md)
- [plot](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-3.12.0.md)
- [plot](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 95.66%, 1.00x faster at 99th %ile)
- [table](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-base.md)
- [plot](bm-20230827-linux-x86_64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed-vs-base.png)

