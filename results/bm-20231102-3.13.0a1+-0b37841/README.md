# Results

- fork: iritkatriel
- version: 3.13.0a1+
- tier 2: False
- commit hash: [0b37841](https://github.com/iritkatriel/cpython/commit/0b37841)
- commit date: 2023-11-02T14:50:18+00:00
- commit merge base: [6a0d7b43df12ab4426badd09d2796e66838129ac](https://github.com/iritkatriel/cpython/commit/6a0d7b43df12ab4426badd09d2796e66838129ac)
- ref: gen_yf

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6734326684)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster (HPT: reliability of 100.00%, 1.27x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-3.10.4.md)
- [plot](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-3.11.0.md)
- [plot](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster (HPT: reliability of 99.87%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-3.12.0.md)
- [plot](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x slower (HPT: reliability of 100.00%, 1.00x slower at 99th %ile)
- [table](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-base.md)
- [plot](bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1%2B-0b37841-vs-base.png)

