# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: True
- commit hash: [4d1e295](https://github.com/faster%2dcpython/cpython/commit/4d1e295)
- commit date: 2023-11-12T06:35:45+00:00
- commit merge base: [a519b87958da0b340caef48349d6e3c23c98e47e](https://github.com/faster%2dcpython/cpython/commit/a519b87958da0b340caef48349d6e3c23c98e47e)
- ref: deopts_with_ip

## linux x86_64 (azure)

- [pystats raw](bm-20231112-azure-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-pystats.json)
- [pystats table](bm-20231112-azure-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-pystats.md)

### vs. base

- [pystats diff](bm-20231112-azure-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6865945502)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-3.10.4.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 97.45%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-3.11.0.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-3.12.0.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x faster (HPT: reliability of 99.92%, 1.00x faster at 99th %ile)
- [table](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-base.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-deopts_with_ip-3.13.0a1%2B-4d1e295-vs-base.png)

