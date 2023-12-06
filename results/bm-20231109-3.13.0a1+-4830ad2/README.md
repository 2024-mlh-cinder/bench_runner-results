# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: False
- commit hash: [4830ad2](https://github.com/faster%2dcpython/cpython/commit/4830ad2)
- commit date: 2023-11-09T15:26:57+00:00
- commit merge base: [97c4c06d0d235aad00e5b6b10af8b8d68c889b9b](https://github.com/faster%2dcpython/cpython/commit/97c4c06d0d235aad00e5b6b10af8b8d68c889b9b)
- ref: faster_tier_2_interp

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6813914394)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-3.10.4.md)
- [plot](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 98.26%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-3.11.0.md)
- [plot](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-3.12.0.md)
- [plot](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.07x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-base.md)
- [plot](bm-20231109-linux-x86_64-faster%252dcpython-faster_tier_2_interp-3.13.0a1%2B-4830ad2-vs-base.png)

