# Results

- fork: brandtbucher
- version: 3.13.0a2+
- tier 2: False
- commit hash: [00abf88](https://github.com/brandtbucher/cpython/commit/00abf88)
- commit date: 2023-11-29T17:19:59-08:00
- commit merge base: [48dfd74a9db9d4aa9c6f23b4a67b461e5d977173](https://github.com/brandtbucher/cpython/commit/48dfd74a9db9d4aa9c6f23b4a67b461e5d977173)
- ref: justin_mmap

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7041618060)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.18x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-3.10.4.md)
- [plot](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 86.05%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-3.11.0.md)
- [plot](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower \* (HPT: reliability of 99.82%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-3.12.0.md)
- [plot](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- [table](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-base.md)
- [plot](bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2%2B-00abf88-vs-base.png)

