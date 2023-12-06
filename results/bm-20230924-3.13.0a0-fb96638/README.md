# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [fb96638](https://github.com/brandtbucher/cpython/commit/fb96638)
- commit date: 2023-09-24T06:37:38-07:00
- commit merge base: [8a82bff12c8e6c6c204c8a48ee4993d908ec4b73](https://github.com/brandtbucher/cpython/commit/8a82bff12c8e6c6c204c8a48ee4993d908ec4b73)
- ref: justin_operands

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6305944025)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.19x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-3.10.4.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 90.02%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-3.11.0.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.66%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-3.12.0.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-base.md)
- [plot](bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638-vs-base.png)

