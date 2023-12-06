# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: True
- commit hash: [14aea56](https://github.com/gvanrossum/cpython/commit/14aea56)
- commit date: 2023-11-17T15:11:51-08:00
- commit merge base: [dabc0d77b21d8cc619a2ffcf859f684b6c1c7020](https://github.com/gvanrossum/cpython/commit/dabc0d77b21d8cc619a2ffcf859f684b6c1c7020)
- ref: for_iter_uop

## linux x86_64 (azure)

- [pystats raw](bm-20231117-azure-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-pystats.json)
- [pystats table](bm-20231117-azure-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-pystats.md)

### vs. base

- [pystats diff](bm-20231117-azure-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6910571427)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-3.10.4.md)
- [plot](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.09x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-3.11.0.md)
- [plot](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.12x slower \* (HPT: reliability of 100.00%, 1.06x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-3.12.0.md)
- [plot](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-base.md)
- [plot](bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1%2B-14aea56-vs-base.png)

