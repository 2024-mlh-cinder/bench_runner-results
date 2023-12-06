# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: True
- commit hash: [58d77db](https://github.com/faster%2dcpython/cpython/commit/58d77db)
- commit date: 2023-11-16T21:49:48+00:00
- commit merge base: [0ee2d77331f2362fcaab20cc678530b18e467e3c](https://github.com/faster%2dcpython/cpython/commit/0ee2d77331f2362fcaab20cc678530b18e467e3c)
- ref: optimize_globals_to_

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6905261349)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-3.10.4.md)
- [plot](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 96.94%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-3.11.0.md)
- [plot](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-3.12.0.md)
- [plot](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 99.98%, 1.00x slower at 99th %ile)
- [table](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-base.md)
- [plot](bm-20231116-linux-x86_64-faster%252dcpython-optimize_globals_to_-3.13.0a1%2B-58d77db-vs-base.png)

