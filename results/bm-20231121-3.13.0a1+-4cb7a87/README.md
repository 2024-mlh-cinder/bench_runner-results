# Results

- fork: brandtbucher
- version: 3.13.0a1+
- tier 2: False
- commit hash: [4cb7a87](https://github.com/brandtbucher/cpython/commit/4cb7a87)
- commit date: 2023-11-21T06:23:23-08:00
- commit merge base: [1619f4350ee431d2fa2f7c0b89702e897d9d14a2](https://github.com/brandtbucher/cpython/commit/1619f4350ee431d2fa2f7c0b89702e897d9d14a2)
- ref: justin

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7024420266)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87-vs-3.10.4.md)
- [plot](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.92%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87-vs-3.11.0.md)
- [plot](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87-vs-3.12.0.md)
- [plot](bm-20231121-linux-x86_64-brandtbucher-justin-3.13.0a1%2B-4cb7a87-vs-3.12.0.png)

