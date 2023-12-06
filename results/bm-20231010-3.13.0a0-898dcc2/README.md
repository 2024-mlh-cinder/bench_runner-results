# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [898dcc2](https://github.com/brandtbucher/cpython/commit/898dcc2)
- commit date: 2023-10-10T14:45:03+02:00
- commit merge base: [982f1b7d6dc2f13b9607ce092e36e32972e3702c](https://github.com/brandtbucher/cpython/commit/982f1b7d6dc2f13b9607ce092e36e32972e3702c)
- ref: justin

## linux x86_64 (azure)

- [pystats raw](bm-20231010-azure-x86_64-brandtbucher-justin-3.13.0a0-898dcc2-pystats.json)
- [pystats table](bm-20231010-azure-x86_64-brandtbucher-justin-3.13.0a0-898dcc2-pystats.md)

### vs. base

- [pystats diff](bm-20231010-azure-x86_64-brandtbucher-justin-3.13.0a0-898dcc2-pystats-vs-base.md)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6476485262)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2.json)

### vs. 3.10.4

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.84%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-3.10.4.md)
- [plot](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.99%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-3.11.0.md)
- [plot](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.10x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-3.12.0.md)
- [plot](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.08x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- [table](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-base.md)
- [plot](bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2-vs-base.png)

