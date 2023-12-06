# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: True
- commit hash: [a2c4f00](https://github.com/gvanrossum/cpython/commit/a2c4f00)
- commit date: 2023-11-19T11:22:02-08:00
- commit merge base: [eb3c94ea669561a0dfacaca715d4b2723bb2c6f4](https://github.com/gvanrossum/cpython/commit/eb3c94ea669561a0dfacaca715d4b2723bb2c6f4)
- ref: faster_uops

## linux x86_64 (azure)

- [pystats raw](bm-20231119-azure-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-pystats.json)
- [pystats table](bm-20231119-azure-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-pystats.md)

### vs. base

- [pystats diff](bm-20231119-azure-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6922482470)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-3.10.4.md)
- [plot](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.94%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-3.11.0.md)
- [plot](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-3.12.0.md)
- [plot](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-base.md)
- [plot](bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1%2B-a2c4f00-vs-base.png)

