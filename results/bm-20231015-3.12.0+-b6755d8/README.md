# Results

- fork: python
- version: 3.12.0+
- tier 2: False
- commit hash: [b6755d8](https://github.com/python/cpython/commit/b6755d8)
- commit date: 2023-10-15T07:08:40+05:30
- ref: 3.12

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6520828023)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8-vs-3.10.4.md)
- [plot](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.98%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8-vs-3.11.0.md)
- [plot](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8-vs-3.12.0.md)
- [plot](bm-20231015-linux-x86_64-python-3.12-3.12.0%2B-b6755d8-vs-3.12.0.png)

