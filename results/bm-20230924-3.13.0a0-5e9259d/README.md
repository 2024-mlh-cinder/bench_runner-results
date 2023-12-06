# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [5e9259d](https://github.com/brandtbucher/cpython/commit/5e9259d)
- commit date: 2023-09-24T14:44:10-07:00
- commit merge base: [8a82bff12c8e6c6c204c8a48ee4993d908ec4b73](https://github.com/brandtbucher/cpython/commit/8a82bff12c8e6c6c204c8a48ee4993d908ec4b73)
- ref: 5e9259d5db5f6e94cadc

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6318014315)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-3.10.4.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 79.80%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-3.11.0.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 85.56%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-3.12.0.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-base.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d-vs-base.png)

