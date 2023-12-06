# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: True
- commit hash: [dbd826e](https://github.com/mdboom/cpython/commit/dbd826e)
- commit date: 2023-11-20T15:02:39-05:00
- commit merge base: [c4c63211e83aa50927f3f1e57eacfaf4952ed228](https://github.com/mdboom/cpython/commit/c4c63211e83aa50927f3f1e57eacfaf4952ed228)
- ref: test_branch3

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6935200763)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-3.10.4.md)
- [plot](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.89%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-3.11.0.md)
- [plot](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-3.12.0.md)
- [plot](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.04x faster (HPT: reliability of 100.00%, 1.01x faster at 99th %ile)
- [table](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-base.md)
- [plot](bm-20231120-linux-x86_64-mdboom-test_branch3-3.13.0a1%2B-dbd826e-vs-base.png)

