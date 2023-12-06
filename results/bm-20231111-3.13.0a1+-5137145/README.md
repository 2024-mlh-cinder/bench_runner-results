# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: False
- commit hash: [5137145](https://github.com/brandtbucher/cpython/commit/5137145)
- commit date: 2023-11-11T12:17:11-08:00
- commit merge base: [fa84e5fe0a3bd8e77c33b20867d71ac6bee270f9](https://github.com/brandtbucher/cpython/commit/fa84e5fe0a3bd8e77c33b20867d71ac6bee270f9)
- ref: justin_no_elf_hacks

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6843564879)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.md)
- [plot](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 51.40%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.md)
- [plot](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 86.39%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.md)
- [plot](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.md)
- [plot](bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6843564879)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145.json)

### vs. 3.10.4

- Geometric mean: 1.26x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.md)
- [plot](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x faster \* (HPT: reliability of 84.62%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.md)
- [plot](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.md)
- [plot](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.02x slower (HPT: reliability of 99.95%, 1.00x slower at 99th %ile)
- [table](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.md)
- [plot](bm-20231111-pythonperf2-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6843564879)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.md)
- [plot](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.md)
- [plot](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 73.15%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.md)
- [plot](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.md)
- [plot](bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6843564879)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster (HPT: reliability of 100.00%, 1.09x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.md)
- [plot](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower (HPT: reliability of 99.98%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.md)
- [plot](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.md)
- [plot](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.03x slower (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- [table](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.md)
- [plot](bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1%2B-5137145-vs-base.png)

