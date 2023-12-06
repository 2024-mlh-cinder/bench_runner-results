# Results

- fork: gvanrossum
- version: 3.13.0a0
- tier 2: False
- commit hash: [8ab398d](https://github.com/gvanrossum/cpython/commit/8ab398d)
- commit date: 2023-10-03T16:05:03-07:00
- commit merge base: [625ecbe92eb69d2850c2e6dbe9538e9b1a098baa](https://github.com/gvanrossum/cpython/commit/625ecbe92eb69d2850c2e6dbe9538e9b1a098baa)
- ref: split_uops

## linux x86_64 (azure)

- [pystats raw](bm-20231003-azure-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-pystats.json)
- [pystats table](bm-20231003-azure-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-pystats.md)

### vs. base

- [pystats diff](bm-20231003-azure-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6399914137)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d.json)

### vs. 3.10.4

- Geometric mean: 1.32x faster \* (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-3.10.4.md)
- [plot](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.79%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-3.11.0.md)
- [plot](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.96%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-3.12.0.md)
- [plot](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 99.88%, 1.00x faster at 99th %ile)
- [table](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-base.md)
- [plot](bm-20231003-linux-x86_64-gvanrossum-split_uops-3.13.0a0-8ab398d-vs-base.png)

