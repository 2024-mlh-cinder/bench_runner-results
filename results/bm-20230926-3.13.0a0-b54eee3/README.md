# Results

- fork: gvanrossum
- version: 3.13.0a0
- tier 2: False
- commit hash: [b54eee3](https://github.com/gvanrossum/cpython/commit/b54eee3)
- commit date: 2023-09-26T21:26:46-07:00
- commit merge base: [fbfec5642edd9d7690bbff088ee43c08e8067044](https://github.com/gvanrossum/cpython/commit/fbfec5642edd9d7690bbff088ee43c08e8067044)
- ref: load_attr_uops

## linux x86_64 (azure)

- [pystats raw](bm-20230926-azure-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-pystats.json)
- [pystats table](bm-20230926-azure-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-pystats.md)

### vs. base

- [pystats diff](bm-20230926-azure-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6328248104)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-3.10.4.md)
- [plot](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 93.26%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-3.11.0.md)
- [plot](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 98.85%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-3.12.0.md)
- [plot](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 88.93%, 1.00x faster at 99th %ile)
- [table](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-base.md)
- [plot](bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3-vs-base.png)

