# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: False
- commit hash: [f362f9a](https://github.com/mdboom/cpython/commit/f362f9a)
- commit date: 2023-11-20T15:25:48-05:00
- commit merge base: [8deb8bc2e5af0e229df87002ee8e0b0c1383f572](https://github.com/mdboom/cpython/commit/8deb8bc2e5af0e229df87002ee8e0b0c1383f572)
- ref: alternative_workarou

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935403709)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a.json)

### vs. 3.10.4

- Geometric mean: 1.34x faster \* (HPT: reliability of 100.00%, 1.26x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-3.10.4.md)
- [plot](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-3.11.0.md)
- [plot](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-3.12.0.md)
- [plot](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 99.85%, 1.00x faster at 99th %ile)
- [table](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-base.md)
- [plot](bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1%2B-f362f9a-vs-base.png)

