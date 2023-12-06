# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: True
- commit hash: [a9f3983](https://github.com/faster%2dcpython/cpython/commit/a9f3983)
- commit date: 2023-11-12T00:04:47+00:00
- commit merge base: [16055c160412544e2a49794aaf3aa70c584f843a](https://github.com/faster%2dcpython/cpython/commit/16055c160412544e2a49794aaf3aa70c584f843a)
- ref: faster_tier_2_interp

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6863448890)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-3.10.4.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.12%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-3.11.0.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-3.12.0.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 99.49%, 1.00x faster at 99th %ile)
- [table](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-base.md)
- [plot](bm-20231112-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-a9f3983-vs-base.png)

