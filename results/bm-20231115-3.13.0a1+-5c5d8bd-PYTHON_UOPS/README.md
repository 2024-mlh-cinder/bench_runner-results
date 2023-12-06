# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: True
- commit hash: [5c5d8bd](https://github.com/gvanrossum/cpython/commit/5c5d8bd)
- commit date: 2023-11-15T16:14:17-08:00
- commit merge base: [a6465605c1417792ec04ced88340cdf104a402b6](https://github.com/gvanrossum/cpython/commit/a6465605c1417792ec04ced88340cdf104a402b6)
- ref: for_iter_uop

## linux x86_64 (azure)

- [pystats raw](bm-20231115-azure-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-pystats.json)
- [pystats table](bm-20231115-azure-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-pystats.md)

### vs. base

- [pystats diff](bm-20231115-azure-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6886653372)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.10x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-3.10.4.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-3.11.0.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.08x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-3.12.0.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-base.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-5c5d8bd-vs-base.png)

