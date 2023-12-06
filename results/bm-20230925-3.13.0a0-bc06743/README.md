# Results

- fork: python
- version: 3.13.0a0
- tier 2: False
- commit hash: [bc06743](https://github.com/python/cpython/commit/bc06743)
- commit date: 2023-09-25T16:02:04+00:00
- ref: bc06743533b5fea2d5ec

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6324495166)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743-vs-3.10.4.md)
- [plot](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 94.79%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743-vs-3.11.0.md)
- [plot](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.84%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743-vs-3.12.0.md)
- [plot](bm-20230925-linux-x86_64-python-bc06743533b5fea2d5ec-3.13.0a0-bc06743-vs-3.12.0.png)

