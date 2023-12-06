# Results

- fork: gvanrossum
- version: 3.13.0a1+
- tier 2: False
- commit hash: [c681cde](https://github.com/gvanrossum/cpython/commit/c681cde)
- commit date: 2023-11-15T08:41:15-08:00
- commit merge base: [4bbb367ba65e1df7307f7c6a33afd3c369592188](https://github.com/gvanrossum/cpython/commit/4bbb367ba65e1df7307f7c6a33afd3c369592188)
- ref: gil_counter

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6880279331)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.20x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-3.10.4.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 90.85%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-3.11.0.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.95%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-3.12.0.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-base.md)
- [plot](bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1%2B-c681cde-vs-base.png)

