# Results

- fork: python
- version: 3.13.0a1+
- tier 2: False
- commit hash: [7810b69](https://github.com/python/cpython/commit/7810b69)
- commit date: 2023-11-03T10:37:46+01:00
- commit merge base: [7bcf184dacf5cfbcb16b4c2735472314b03a009e](https://github.com/python/cpython/commit/7bcf184dacf5cfbcb16b4c2735472314b03a009e)
- ref: 7810b6981ac663b77bc9

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6744730779)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69-vs-3.10.4.md)
- [plot](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69-vs-3.11.0.md)
- [plot](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.77%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69-vs-3.12.0.md)
- [plot](bm-20231103-linux-x86_64-python-7810b6981ac663b77bc9-3.13.0a1%2B-7810b69-vs-3.12.0.png)

