# Results

- fork: brandtbucher
- version: 3.13.0a0
- tier 2: False
- commit hash: [1799b79](https://github.com/brandtbucher/cpython/commit/1799b79)
- commit date: 2023-10-02T15:55:32-07:00
- commit merge base: [4596c76d1a7650fd4650c814dc1d40d664cd8fb4](https://github.com/brandtbucher/cpython/commit/4596c76d1a7650fd4650c814dc1d40d664cd8fb4)
- ref: justin_elf

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6394609255)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.17x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.md)
- [plot](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 97.16%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.md)
- [plot](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.53%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.md)
- [plot](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.md)
- [plot](bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6394609255)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.md)
- [plot](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 62.29%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.md)
- [plot](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.md)
- [plot](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.md)
- [plot](bm-20231002-pythonperf2-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6394609255)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79.json)

### vs. 3.10.4

- Geometric mean: 1.06x faster \* (HPT: reliability of 97.82%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.md)
- [plot](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.md)
- [plot](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.12x slower \* (HPT: reliability of 100.00%, 1.06x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.md)
- [plot](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.10x slower (HPT: reliability of 100.00%, 1.06x slower at 99th %ile)
- [table](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.md)
- [plot](bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6394609255)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.md)
- [plot](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 96.90%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.md)
- [plot](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.24%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, pprint_pformat, pprint_safe_repr, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.md)
- [plot](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: 🔴 pprint_pformat, pprint_safe_repr
- [table](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.md)
- [plot](bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79-vs-base.png)

