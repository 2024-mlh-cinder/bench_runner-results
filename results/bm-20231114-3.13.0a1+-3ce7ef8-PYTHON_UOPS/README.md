# Results

- fork: mdboom
- version: 3.13.0a1+
- tier 2: True
- commit hash: [3ce7ef8](https://github.com/mdboom/cpython/commit/3ce7ef8)
- commit date: 2023-11-14T08:21:04-05:00
- commit merge base: [4f04172c9287c507f1426e02ddfc432f1f3ade54](https://github.com/mdboom/cpython/commit/4f04172c9287c507f1426e02ddfc432f1f3ade54)
- ref: test_branch

## linux x86_64 (azure)

- [pystats raw](bm-20231114-azure-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-pystats.json)
- [pystats table](bm-20231114-azure-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-pystats.md)

### vs. base

- [pystats diff](bm-20231114-azure-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6864228122)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8.json)

### vs. 3.10.4

- Geometric mean: 1.24x faster \* (HPT: reliability of 100.00%, 1.14x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-3.10.4.md)
- [plot](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 99.27%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-3.11.0.md)
- [plot](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-3.12.0.md)
- [plot](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 91.54%, 1.00x slower at 99th %ile)
- [table](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-base.md)
- [plot](bm-20231114-linux-x86_64-mdboom-test_branch-3.13.0a1%2B-3ce7ef8-vs-base.png)

