# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [07fb485](https://github.com/brandtbucher/cpython/commit/07fb485)
- commit date: 2023-10-11T15:47:19+02:00
- commit merge base: [982f1b7d6dc2f13b9607ce092e36e32972e3702c](https://github.com/brandtbucher/cpython/commit/982f1b7d6dc2f13b9607ce092e36e32972e3702c)
- ref: justin

## linux x86_64 (azure)

- [pystats raw](bm-20231011-azure-x86_64-brandtbucher-justin-3.13.0a0-07fb485-pystats.json)
- [pystats table](bm-20231011-azure-x86_64-brandtbucher-justin-3.13.0a0-07fb485-pystats.md)

### vs. base

- [pystats diff](bm-20231011-azure-x86_64-brandtbucher-justin-3.13.0a0-07fb485-pystats-vs-base.md)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6489522294)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.10.4.md)
- [plot](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 84.15%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.11.0.md)
- [plot](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.12.0.md)
- [plot](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-base.md)
- [plot](bm-20231011-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-07fb485-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6489522294)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485.json)

### vs. 3.10.4

- Geometric mean: 1.06x faster \* (HPT: reliability of 98.12%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.10.4.md)
- [plot](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.11.0.md)
- [plot](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.12x slower \* (HPT: reliability of 100.00%, 1.07x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.12.0.md)
- [plot](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- [table](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-base.md)
- [plot](bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485-vs-base.png)

